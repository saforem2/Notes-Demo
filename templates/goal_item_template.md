---
tags: goal
Progress: 0
Target: {{VALUE:🎯 Target (number)}}
Timespan: {{VALUE:10 Years, 5 Years, 3 Years, 1 Year, 6 Months, 1 Month, 1 Week}}
Creation date:
Deadline:
---
%%
Bar:: `$= dv.view('progress-bar', {file: '{{DATE}} - {{VALUE:Goal}}'})`
Projects:: `$= const projects = dv.page('{{DATE}} - {{VALUE:Goal}}').file.inlinks.where(p => { const mp = dv.page(p.path); return mp.tags?.contains('project') && mp.status === 'In Progress'}); if (projects.length > 0) { dv.header(4, projects.length > 1 ? "Projects" : "Project"); dv.list(projects) }`
%%

## Why is this goal important to you?
-

---
## What does success look like? Why is this goal important?
- 

---
## What are the Key steps you will take to accomplish this goal?
- 
---
### Date created:
### Deadline: 
---
## ACTION PLAN