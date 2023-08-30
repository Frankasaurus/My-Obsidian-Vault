---
type: "Player Character"
player: "Melle"
campaign: "StracciaD&D 2"
member: "All sessions"
member_status: "Current"
name_first: "Roderick"
name_last: ""
name_full: "Roderick"
name_aka: [""]
creature_type: Humanoid
creature_race: "Half-Elf"
creature_subrace: "Wood"
gender: Male
age: ??
place_of_birth: "The Wovens"
class: "Warlock"
subclass: "Pact of the Fiend"
background: Outlander
level: 7
status: Alive
hit_points: 28
armor_class: 12
stat_str: 8
stat_dex: 10
stat_con: 14
stat_int: 9
stat_wis: 14
stat_cha: 18
languages: [Common, Elvish]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Roderick1.png|cover hsmall]]  
> ###### Base Info
> | | |  
> |---|---|  
> | **Type** | `= this.type` |
> | **Player** | `= link(this.player)` |
> ###### Character Information  
> | | |  
> |---|---|  
> | **Name** | `= this.name_full` |
> | **Gender** | `=this.gender` | 
> | **Creature Type** | `= this.creature_type` |
> | **Race** | `= link(this.creature_race)` `= choice(this.creature_subrace = "", "", "(")` `= this.creature_subrace` `= choice(this.creature_subrace = "", "", ")")`|  
> | **Class** | `= link(this.class)` `= choice(this.subclass = "", "", "(")` `= this.subclass` `= choice(this.subclass = "", "", ")")`|  
> | **Born** | `=link(this.place_of_birth)` , `=this.age` years ago|  
> | **Languages** | `=this.languages` |  
> | **Family** | - Unnamed father and mother |
> | **Connections** | - [[Party]] (member) |
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