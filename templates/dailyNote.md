---
tags:
  - daily
  - <% tp.date.now("YYYY/MM/DD", 0, tp.file.title, "(📅) YYYY-MM-DD") %>
full-date: <% tp.file.title %>
week: <% tp.date.now("YYYY/[W]ww", 0, tp.file.title, "YYYY-MM-DD") %>
month: <% tp.date.now("YYYY/MM-MMMM", 0, tp.file.title, "YYYY-MM-DD") %>
year: <% tp.date.now("YYYY", 0, tp.file.title, "YYYY-MM-DD") %>
rating: null
---

#{{date:YYYY}}/{{date:YYYY-MM}}/{{date:YYYY-MM-DD}} [🍋](file:///Applications/Setapp/Grapefruit.app/Contents/Macos/Grapefruit) [📆](https://exist.io/mood/timeline/edit/{{date:YYYY-MM-DD}}) 

[[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>|⇦ Yesterday]] ⁝ [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>|Tomorrow ⇨]]

# <% tp.date.now("dddd - MMMM Do YYYY", 0, tp.file.title, "(📅) YYYY-MM-DD") %>
## 🏢 Work
## 🏡 Personal
### 📒 Journal
## Links

## Ideas

## DataView

> [!done]- Completed Today
> ```dataview
> TASK WHERE completion = date("{{date:YYYY-MM-DD}}")
>   AND due != date("{{date:YYYY-MM-DD}}")
> ```

> [!bomb]- Created Today
> ```dataview
> TABLE string(split(string(file.ctime), " - ")[0]) as "Created", file.mtime as "Last Modified"
> WHERE contains(file.path, "{{date:YYYY-MM-DD}}")
>   OR (file.cday = date("{{date:YYYY-MM-DD}}") AND !regexmatch("^\d{4}-\d{2}-\d{2}", file.name))
> SORT file.name ASC
> ```

> [!changes]- Last Modified Today
> ```dataview
> TABLE string(split(string(file.mtime), " - ")[0]) as "Last Modified"
> WHERE !contains(file.path, "{{date:YYYY-MM-DD}}")
>   AND file.mday = date("{{date:YYYY-MM-DD}}")
> SORT file.mtime DESC
> ```

---
