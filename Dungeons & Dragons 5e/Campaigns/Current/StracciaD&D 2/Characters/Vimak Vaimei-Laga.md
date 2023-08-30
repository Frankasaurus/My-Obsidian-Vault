---
type: "Player Character"
player: "Roy"
campaign: "StracciaD&D 2"
member: "All sessions"
member_status: "Current"
name_first: "Vimak"
name_last: "Vaimei-Laga"
name_full: "Vimak \"Lonehunter\" Vaimei-Laga"
name_aka: ["Ysmir Hardrada (Borrowed name)", "Lonehunter (Clan name)"]
creature_type: Humanoid
creature_race: "Goliath"
creature_subrace: ""
gender: Male
age: 30
place_of_birth: "Devostina Alps"
class: "Paladin"
subclass: "Oath of Devotion"
background: Custom
level: 7
status: Alive
hit_points: 31
armor_class: 17
stat_str: 13
stat_dex: 11
stat_con: 14
stat_int: 15
stat_wis: 11
stat_cha: 12
languages: [Common, Elvish, Giant]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Vimak1.png|cover hsmall]]  
> ###### Base Info
> | | |  
> |---|---|  
> | **Type** | `= this.type` |
> | **Player** | `= link(this.player)` |
> ###### Character Information  
> | | |  
> |---|---|  
> | **Name** | `= this.name_full` |
> | **Aliases** | `= this.name_aka` |
> | **Gender** | `=this.gender` | 
> | **Creature Type** | `= this.creature_type` |
> | **Race** | `= link(this.creature_race)` `= choice(this.creature_subrace = "", "", "(")` `= this.creature_subrace` `= choice(this.creature_subrace = "", "", ")")`|  
> | **Class** | `= link(this.class)` `= choice(this.subclass = "", "", "(")` `= this.subclass` `= choice(this.subclass = "", "", ")")`|  
> | **Born** | `=link(this.place_of_birth)` , `=this.age` years ago|  
> | **Languages** | `=this.languages` |  
> | **Family** | - [[Kuori "Bearkiller"]] (father)<br>- [[Lo-Kag "Wordpainter"]] (mother)<br>- [[Aukan "Keepeye"]] (brother, deceased) |
> | **Connections** | - [[Party]] (member)<br>- [[Gathakeaku Clan]] (ex-member, banished)<br>- [[Henevar]] (Oath patron) |
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