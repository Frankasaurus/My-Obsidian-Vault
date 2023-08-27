---
type: "Player Character"
player: "Lise"
campaign: "StracciaD&D 2"
member: "From session 9 onwards"
member_status: "Current"
name_first: "Robyn"
name_last: ""
name_full: "Robyn"
name_aka: [""]
creature_type: Humanoid
creature_race: "Half-Orc"
creature_subrace: ""
gender: Female
age: 24
place_of_birth: "Torpe"
class: "Monk"
subclass: "Way of the Astral Self"
background: Entertainer
level: 7
status: Alive
hit_points: ??
armor_class: 14 
stat_str: 13
stat_dex: 16
stat_con: 14
stat_int: 11
stat_wis: 13
stat_cha: 14
languages: [Common, Orcish]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Robyn1.png|cover hsmall]]  
> ###### Base Info
> | | |  
> |---|---|  
> | **Type** | `= this.type` |
> | **Player** | `= this.player` |
> ###### Character Information  
> | | |  
> |---|---|  
> | **Name** | `= this.name_full` |
> | **Gender** | `=this.gender` | 
> | **Creature Type** | `=this.creature_type` |
> | **Race** | `= this.creature_race` `= choice(this.creature_subrace = "", "", "(")` `= this.creature_subrace` `= choice(this.creature_subrace = "", "", ")")`|  
> | **Class** | `= this.class` `= choice(this.subclass = "", "", "(")` `= this.subclass` `= choice(this.subclass = "", "", ")")`|  
> | **Born** | `=this.place_of_birth` , `=this.age` years ago|  
> | **Languages** | `=this.languages` |  
> | **Family** | - Rhayn (mother)<br>- Linzo (father) |
> | **Connections** | - Mozillin Brown's Bazaar (member) |
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