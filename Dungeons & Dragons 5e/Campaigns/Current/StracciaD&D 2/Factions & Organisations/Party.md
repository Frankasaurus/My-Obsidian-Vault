# Members
## Current members
```dataview
TABLE member AS Since, status AS Status
FROM "Dungeons & Dragons 5e/Campaigns/Current/StracciaD&D 2/Characters"
WHERE member_status = "Current"
SORT file.name ASC
```
## Previous members
```dataview
TABLE member AS Since, status AS Status
FROM "Dungeons & Dragons 5e/Campaigns/Current/StracciaD&D 2/Characters"
WHERE member_status != "Current"
SORT file.name ASC
```
