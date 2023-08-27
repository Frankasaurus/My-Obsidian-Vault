---
type: "Player Character"
player: "Chris"
campaign: "StracciaD&D 2"
member: "From sessions 1 to 12"
member_status: "Previous"
name_first: "Bulblin"
name_last: "Wormbone"
name_full: "Bulblin Wormbone"
name_aka: [""]
creature_type: Humanoid
creature_race: "Goblin"
creature_subrace: ""
gender: Male
age: ??
place_of_birth: "Jaxos Isle (Bloeming Isles)"
class: "Ranger"
subclass: "Beastmaster"
background: Criminal
level: 3
status: Alive
hit_points: 28
armor_class: 15
stat_str: 13
stat_dex: 17
stat_con: 12
stat_int: 7
stat_wis: 14
stat_cha: 12
languages: [Common, Goblin, Elvish, Infernal]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Image.jpg|cover hsmall]]  
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

`=this.name_first` `=this.name_last` is a `=this.creature_subrace` `=this.creature_race` `=this.subclass` `=this.class`. `=choice(this.gender = "Male", "He", "She")` was played by `=this.player`. 
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