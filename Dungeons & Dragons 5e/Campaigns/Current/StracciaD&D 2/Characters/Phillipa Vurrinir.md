---
type: "Player Character"
player: "Hanne"
campaign: "StracciaD&D 2"
member: "From session 29 onwards"
member_status: "Current"
name_first: "Phillipa"
name_last: "Vurrinir"
name_full: "Phillipa Vurrinir"
name_aka: ["Misthold"]
creature_type: Humanoid
creature_race: "Elf"
creature_subrace: "Wood"
gender: Female
age: 236
place_of_birth: "Unknown"
class: "Rogue"
subclass: "Thief"
background: Criminal
level: 7
status: Alive
hit_points: 59
armor_class: 14
stat_str: 12
stat_dex: 18
stat_con: 15
stat_int: 11
stat_wis: 16
stat_cha: 9
languages: [Common, Elvish, "Thieves' Cant"]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Phillipa1.jpg|cover hsmall]]  
> ###### Base Info
> | | |  
> |---|---|  
> | **Type** | `= this.type` |
> | **Player** | `= this.player` |
> ###### Character Information  
> | | |  
> |---|---|  
> | **Name** | `= this.name_full` |
> | **Aliases** | `= this.name_aka` |
> | **Gender** | `=this.gender` | 
> | **Creature Type** | `=this.creature_type` |
> | **Race** | `= this.creature_race` `= choice(this.subclass, "(", "")` `= this.creature_subrace` `= choice(this.subclass, ")", "")`|  
> | **Class** | `= this.class` `= choice(this.subclass, "(", "")` `= this.subclass` `= choice(this.subclass, ")", "")`|  
> | **Born** | `=this.place_of_birth` , `=this.age` years ago|  
> | **Languages** | `=this.languages` |  
> | **Family** | Name (relation) |
> | **Connections** | Name (relation) |
> | **Status** | `=this.status` |
> | **Sessions** | `=this.member` |
> ###### Stats
> | | | | |
> |---|---|---|---|
> | **Level** | `=this.level` | **HP** | `=this.hit_points` |
> | **AC** | `=this.armor_class` | | |
> | **Str** | `=this.stat_str` | **Int** | `=this.stat_int` |
> | **Dex** | `=this.stat_dex` | **Wis** | `=this.stat_wis` |
> | **Con** | `=this.stat_con` | **Cha** | `=this.stat_cha` |

`=this.name_first` `=this.name_last` is a `=this.creature_subrace` `=this.creature_race` `=this.subclass` `=this.class`. `=choice(this.gender = "Male", "He", "She")` is played by `=this.player`. 
# Description
## Appearance
Description of appearance.
## Personality
Description of personality.
# Biography
## Before the campaign
Story of before the adventuring party coalesced in Telack.
## Adventures
Story of after meeting the gang.
# Relationships
### Persoon
Is dit nodig?
# Character information
### Quests
Short listing of quests this character is after as an adventurer.
### Notable items
- List of items
- List of items
### Magic items
```dataview
LIST
FROM "Dungeons & Dragons 5e/Campaigns/Current/StracciaD&D 2/Magic Items"
WHERE owner = this.name_first
```
# Trivia
- List of trivia
- List of trivia
- List of trivia