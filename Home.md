---
embedded-path: false
description:
title: Home
---

# 🏡 Home

```dataview
CALENDAR file.ctime
```

> [!changes]+ Recent
> ```dataview
> TASK
> FROM "PeriodicNotes"
> WHERE !completed
> SORT file.day DESC
> LIMIT 20
> GROUP BY file.day
> SORT rows.file.day DESC
> ```

> [!bomb]- Older
> ```dataview
> TASK
> FROM "PeriodicNotes/Daily"
> WHERE !completed
> SORT file.day DESC
> LIMIT 100 
> GROUP BY file.day
> SORT rows.file.day ASC
> ```

> [!DONE]+ Completed
> ```dataview
> TASK
> FROM "PeriodicNotes/Daily"
> WHERE completed
> SORT file.day DESC
> LIMIT 20
> GROUP BY file.day
> SORT rows.file.day DESC
> ```


```dataview
TABLE file.ctime as "Created", file.mtime as "Modified" from "PeriodicNotes" WHERE file.mtime >= date(today) - dur(1 week) OR file.date >= date(today) - dur(1 week)
SORT file.mtime DESC
```