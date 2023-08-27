---
type: "Player Character"
player: "Kim"
campaign: "StracciaD&D 2"
member: "All sessions"
member_status: "Current"
name_first: "Elisabeth"
name_last: "de Dragoness"
name_full: "Elisabeth de Dragoness"
name_aka: ["His free lady Elisabeth"]
creature_type: Humanoid
creature_race: "Tiefling"
creature_subrace: ""
gender: Female
age: 26?
place_of_birth: "Dragoness Barony"
class: "Sorcerer"
subclass: "Draconic Bloodline"
background: Noble
level: 6
status: Alive
hit_points: ??
armor_class: 15
stat_str: 8
stat_dex: 14
stat_con: 12
stat_int: 10
stat_wis: 12
stat_cha: 19
languages: [Common, Infernal, Draconic]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Elisabeth1.png|cover hsmall]]  
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
> | **Race** | `= this.creature_race` `= choice(this.creature_subrace = "", "", "(")` `= this.creature_subrace` `= choice(this.creature_subrace = "", "", ")")`|  
> | **Class** | `= this.class` `= choice(this.subclass = "", "", "(")` `= this.subclass` `= choice(this.subclass = "", "", ")")`|  
> | **Born** | `=this.place_of_birth` , `=this.age` years ago|  
> | **Languages** | `=this.languages` |  
> | **Family** | - Xavion (vader, Baron de Dragoness)<br>- Willemijn (Mother)<br>- Amenadiel, Benjamin, Charles, Diederick (brothers) |
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