```dataview
TABLE type AS Type, rarity AS Rarity, owner AS Owner
FROM "Dungeons & Dragons 5e/Campaigns/Current/StracciaD&D 2/Magic Items"
WHERE file.name != "_Overview"
SORT file.name ASC
```
