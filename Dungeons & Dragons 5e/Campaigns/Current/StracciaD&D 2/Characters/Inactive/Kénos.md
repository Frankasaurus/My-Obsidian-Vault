---
type: "Player Character"
player: "Lise"
campaign: "StracciaD&D 2"
member: "Session 1 to 9"
member_status: "Previous"
name_first: "Kénos"
name_last: ""
name_full: "Kénos"
name_aka: [""]
creature_type: Construct
creature_race: "Warforged"
creature_subrace: ""
gender: Female
age: ??
place_of_birth: ""
class: "Fighter"
subclass: "Psi Warrior"
background: Acolyte
level: 3
status: Alive
hit_points: 34
armor_class: 17
stat_str: 14
stat_dex: 15
stat_con: 18
stat_int: 17
stat_wis: 12
stat_cha: 9
languages: [Common, Celestial, Elvish, Orcish]
---
> [!infobox]  
> # `=this.name_first` `=this.name_last`
> ![[Image.jpg|cover hsmall]]  
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
> | **Family** | - Name (relation) |
> | **Connections** | - [[Party]] (ex-member)<br>- [[Teokharis]] (worshipper) |
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
Kénos was created in [[Larchenia]] by a greedy temple leader, who crafted Kenos under the noses of two other leaders, hoping it would become a mighty creation aligning with his deceptive and deceitful personality. Unfortunately, the experiment failed, and Kénos was abandoned and neglected, even though she was built with an experimental anti-gravity type of precious metal called Dusfex. One infiltrator knew differently, a sage, who associated with Kénos within the temple, teaching her about the world and [[Teokharis]].

Kénos embarked on the path of adventurers in search of an identity; she wants to live a life, not remain a machine, and seeks a way to become human. She only claims to be on a crusade, as it sounds less conspicuous. Her journey has taken her from the East to the West of [[Drav-Modesta]], then onward to the Western continents. Upon arriving in [[Telack]], she continued her journey with a troupe of strangers.
## Adventures
Story of after meeting the gang.
# Relationships
## Persoon
Is dit nodig?
# Character information
## Quests
Short listing of quests this character is after as an adventurer.
## Notable items
- List of items
- List of items
## Magic items
```dataview
LIST
FROM "Dungeons & Dragons 5e/Campaigns/Current/StracciaD&D 2/Magic Items"
WHERE owner = this.name_first
```
# Trivia
- List of trivia
- List of trivia
- List of trivia