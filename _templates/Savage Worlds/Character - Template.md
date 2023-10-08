---
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
tags: [swade,character]
agility: d4
smarts: d4
spirit: d4
strength: d4
vigor: d4
skills:
  fighting: d8
---
>[!abstract] Basics
>
> - **Name:** 
> - **Concept:**
> - **Race:**

>[!abstract] Attributes
>
> | Agility | Smarts | Spirit | Strength | Vigor |
> |-|-|-|-|-|
> | `$= this.current().agility ?? "d4"` | `$= this.current().smarts ?? "d4"` | `$= this.current().spirit ?? "d4"` | `$= this.current().strength ?? "d4"` | `$= this.current().vigor ?? "d4"` |

> [!abstract] Derived Attributes
> 
> | Parry | Toughness | Pace |
> |-|-|-|
> | `$= Math.ceil((( this.current().skills['fighting'] ?? "d4" ).replace(/^d/,""))/2+2)` | `$= Math.ceil((this.current().vigor.replace(/^d/,""))/2+2)` | `$= (this.current().pace ?? "6") `

