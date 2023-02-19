---
tags: monthly-note  
month: <% tp.date.now("MM", 0, tp.file.title, "YYYY--WW") %>-<% tp.date.now("MMM", 0, tp.file.title, "gggg-[W]ww") %>  
year: <% tp.date.now("YYYY", 0, tp.file.title, "gggg-[W]ww") %>  
AutoNoteMover: disable
---
###### [[<% tp.date.now("gggg-[W]ww", -7, tp.file.title, "gggg-[W]ww") %>|↶ PREVIOUS WEEK]] ⁝ [[<% tp.date.now("gggg-[W]ww", 7, tp.file.title, "gggg-[W]ww") %>|FOLLOWING WEEK ↷]]  

# ◌ <% tp.file.title %>


> [!INFO]- Daily Ratings
> ```dataviewjs
> dv.span("** 😊 Daily Ratings  😥**") /* optional ⏹️💤⚡⚠🧩↑↓⏳📔💾📁📝🔄📝🔀⌨️🕸️📅🔍✨ */
> const calendarData = {
>     year: 2022,  // (optional) defaults to current year
>     colors: {    // (optional) defaults to green
>         blue:        ["#8cb9ff", "#69a3ff", "#428bff", "#1872ff", "#0058e2"], // first entry is considered default if supplied
>         green:       ["#c6e48b", "#7bc96f", "#49af5d", "#2e8840", "#196127"],
>         red:         ["#ff9e82", "#ff7b55", "#ff4d1a", "#e73400", "#bd2a00"],
>         orange:      ["#ffa244", "#fd7f00", "#dd6f00", "#bf6000", "#9b4e00"],
>         pink:        ["#ff96cb", "#ff70b8", "#ff3a9d", "#ee0077", "#c30062"],
>         orangeToRed: ["#ffdf04", "#ffbe04", "#ff9a03", "#ff6d02", "#ff2c01"]
>     },
>     showCurrentDayBorder: true, // (optional) defaults to true
>     defaultEntryIntensity: 4,   // (optional) defaults to 4
>     intensityScaleStart: 10,    // (optional) defaults to lowest value passed to entries.intensity
>     intensityScaleEnd: 100,     // (optional) defaults to highest value passed to entries.intensity
>     entries: [],                // (required) populated in the DataviewJS loop below
> }
> //DataviewJS loop
> for (let page of dv.pages('"daily notes"').where(p => p.exercise)) {
>     //dv.span("<br>" + page.file.name) // uncomment for troubleshooting
>     const date = new Date(page.file.name);
>     const yyyy = date.getFullYear();
>     let mm = date.getMonth() + 1; // months start at 0!
>     let dd = date.getDate();
>     if (dd < 10) dd = '0' + dd;
>     if (mm < 10) mm = '0' + mm;
>     const fotmattedDate = yyyy + "-" + mm + "-" + dd;
>     calendarData.entries.push({
>         date: formattedDate,     // (required) Format YYYY-MM-DD
>         intensity: page.rating, // (required) the data you want to track, will map color intensities automatically
>         content: "🟊️",           // (optional) Add text to the date cell
>         color: "red",          // (optional) Reference from *calendarData.colors*. If no color is supplied; colors[0] is used
>     })
> }
> renderHeatmapCalendar(this.container, calendarData)
> ```
> 

## Weeks  
```dataview  
TABLE  
month as "Month"  
FROM "PeriodicNotes/Weekly"  
WHERE month = "<% tp.file.title %>"  
```

## Days  
```dataview  
TABLE  
month as "Month"  
FROM "PeriodicNotes/Daily"  
WHERE month = "<% tp.file.title %>"  
```


# {{date:MMMM}}, {{date:YYYY}}

## Outstanding
```tasks
not done
path includes Daily
heading does not include Older
path includes {{date:MMMM}}
hide edit button
```

## Completed ✅
```tasks
done
hide edit button
path includes Daily
heading does not include Older
heading includes {{date:YYYY}}
```