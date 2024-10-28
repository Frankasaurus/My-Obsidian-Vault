---
publish: true
tags:
  - TODO
name_full: Test fullname
name_first: Test Firstname
name_last: Test Lastname
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

`=this.name_first` `=this.name_last` is a `=this.creature_subrace` `=this.creature_race` `=this.subclass` `=this.class`. `=choice(this.gender = "Male", "He", "She")` is played by `=this.player`. 