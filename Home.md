---
created: 2023-07-07 11:29
banner: "![[home-2.jpg]]"
banner_y: 0.77
banner_lock: true
---


> [!abstract] Starting Scene
> ![[fate-rpg.png|right|300]]
> The Society of Curious Personages is a group of skeptics formed in London in 1908. Their motto is "Probare est Credere" - "To Prove is to Believe" and they are vehement about following it.
> Darius Fisher, already an experienced explorer and eager for adventure, joined the Society quite recently. 

# Scenes
`button-scene`

```page-gallery
filter: false
orientation: square
columns: 3
fields:
- file.name
views:
- name: Characters
  from: '-"_templates"'
  where: 'contains(file.tags, "scene") and !contains(file.tags, "archived")'
```

# Characters
`button-character`

```page-gallery
filter: false
orientation: square
columns: 3
fields:
- file.name
views:
- name: Characters
  from: '-"_templates"'
  where: 'contains(file.tags, "character") and !contains(file.tags, "archived")'
```

# Other stuff
`button-npc` `button-place` `button-setting` `button-creature` `button-map`

```page-gallery
filter: false
orientation: square
columns: 3
fields:
- file.name
views:
- name: NPCs
  from: '-"_templates"'
  where: 'contains(file.tags, "npc") and !contains(file.tags, "archived")'
- name: Places
  from: '-"_templates"'
  where: 'contains(file.tags, "place") and !contains(file.tags, "archived")'
- name: Setting Details
  from: '-"_templates"'
  where: 'contains(file.tags, "setting") and !contains(file.tags, "archived")'
- name: Creatures
  from: '-"_templates"'
  where: 'contains(file.tags, "creature") and !contains(file.tags, "archived")'
- name: Maps
  from: '-"_templates"'
  where: 'contains(file.tags, "map") and !contains(file.tags, "archived")'
```

# Mechanics
```dataview
List
From -"_templates"
Where contains(file.tags, "mechanics") and !contains(file.tags, "archived") 
Sort file.name
```
