---
cssclass: clean-embed
tags: weekly-note  
week: '<% tp.date.now("ww", 0, tp.file.title, "gggg-[W]ww") %>'  
month: '<% tp.date.now("YYYY - MM-MMMM", 0, tp.file.title, "YYYY--WW") %>'  
year: '<% tp.date.now("YYYY", 0, tp.file.title, "gggg-[W]ww") %>'  
AutoNoteMover: disable
---
[[<% tp.date.now("gggg-[W]ww", -7, tp.file.title, "gggg-[W]ww") %>|↶ Previous Week]] ⁝ [[<% tp.date.now("gggg-[W]ww", 7, tp.file.title, "gggg-[W]ww") %>|Next Week ↷]]

# Week {{date:YYYY/MM : [W]ww}}
## Activity History
```ActivityHistory
/
```    
## Daily Ratings

# <% tp.file.title %>

## Weekdays

```dataview
TABLE file.mday as "Last Modified"
WHERE week = "{{date:[W]ww}}"
```

---

# Dailies

> [!DARK]- ## Monday
> ![[{{monday:gggg-MM-DD}}]]

> [!DARK]- ## Tuesday
> ![[{{tuesday:gggg-MM-DD}}]]

> [!DARK]- ## Wednesday
> ![[{{wednesday:gggg-MM-DD}}]]

> [!DARK]- ## Thursday
> ![[{{thursday:gggg-MM-DD}}]]

> [!DARK]- ## Friday
> ![[{{friday:gggg-MM-DD}}]]

> [!DARK]- ## Saturday
> ![[{{saturday:gggg-MM-DD}}]]

> [!DARK]- ## Sunday
> ![[{{sunday:gggg-MM-DD}}]]
