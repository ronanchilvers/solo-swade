---
created: 2023-07-07 11:29
banner: "![[zephyria.jpg]]"
banner_y: 0.97999
---
![[swade.png|right|250]]

> [!abstract] Starting Scene
> Zafira Al'Shara, Rakim's patron, has discovered an old map which she believes gives the location of an ancient treasure - the "Desert Star", a magical jewel. She has given Rakim the job of following the map and finding out if it really does lead to the Star or something else entirely.

# Scenes
```button
name Create new scene
type command
action Quickadd: New Scene
```
^button-new-scene
```dataview
List
From -"_templates"
Where contains(file.tags, "scene") and !contains(file.tags, "archived")
Sort file.name desc
```

# Maps
```button
name Create new map
type command
action Quickadd: New Map
```
^button-new-map
```dataview
List 
From -"_templates"
Where contains(file.tags, "map") and !contains(file.tags, "archived")
Sort file.name
```

# Characters
```button
name Create new character
type command
action Quickadd: New Character
```
^button-new-character
```dataview
List 
From -"_templates"
Where contains(file.tags, "character") and !contains(file.tags, "archived")
Sort file.name
```

# NPCs
```button
name Create new npc
type command
action Quickadd: New NPC
```
^button-new-npc
```page-gallery
filter: false
debug: true
views:
- name: NPCs
  from: '-"_templates"'
  where: 'contains(file.tags, "npc") and !contains(file.tags, "archived")'
```

%% ```datavie1w
List summary
From -"_templates"
Where contains(file.tags, "npc") and !contains(file.tags, "archived")
``` %%

# Creatures
```button
name Create new creature
type command
action Quickadd: New Creature
```
^button-new-creature
```dataview
List
From -"_templates"
Where contains(file.tags, "creature") and !contains(file.tags, "archived")
Sort file.name
```

# Setting
```button
name Create new setting detail
type command
action Quickadd: New Setting
```
^button-new-setting
```dataview
List 
From -"_templates"
Where contains(file.tags, "setting") and !contains(file.tags, "archived")
Sort file.name
```

# Places
```button
name Create new place
type command
action Quickadd: New Place
```
^button-new-place
```dataview
List summary 
From -"_templates"
Where contains(file.tags, "place") and !contains(file.tags, "archived")
Sort file.name
```

# Mechanics
```dataview
List
From -"_templates"
Where contains(file.tags, "mechanics") and !contains(file.tags, "archived") 
Sort file.name
```