---
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
tags: [swade,character]
agility: d4
smarts: d4
spirit: d4
strength: d4
vigor: d6
---
> [!foo]
> Toughness: `$= (this.current().vigor.replace(/^d/,""))/2+2`
