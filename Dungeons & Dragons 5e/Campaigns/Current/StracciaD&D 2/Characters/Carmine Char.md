---
type: "Player Character"
player: Kacper
campaign: "StracciaD&D 2"
member: "All sessions"
member_status: "Current"
name_first: Carmine
name_last: Charr
name_full: "Jules Carmine Charr Jr."
name_aka: []
creature_type: Humanoid
creature_race: "Genasi"
creature_subrace: "Fire"
gender: Male
age: 28
place_of_birth: "Dragoness Barony"
class: "Cleric"
subclass: "Light Domain"
background: Acolyte
level: 6
status: Alive
hit_points: 64
armor_class: 16
stat_str: 16
stat_dex: 14
stat_con: 16
stat_int: 10
stat_wis: 17
stat_cha: 10
languages: [Common, Primordial]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Carmine1.png|cover hsmall]]  
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
> | **Family** | - [[Sabine Charr]] (sister) <br>- Jules Charr Sr. (father)<br>- Uknown mother |
> | **Connections** | - Olvex (worshipper)<br>- Hall of Anew (member) |
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
### Karakter
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