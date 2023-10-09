---
created: 2023-07-07 11:29
banner: "![[zephyria.jpg]]"
banner_y: 0.97999
---
![[swade.png|right|250]]

> [!abstract] Starting Scene
> While many western countries are excited about the new researches into electro-arcane energy, there are those who fear it's power. They fear that we don't yet understand the true source of the newly discovered powers. They fear that it may not be what it seems and that we are on the brink of calamity.
> The Society of the Curious is a group of skeptics formed in London in 1928, which aims to discover the truth. Word has reached London of a strange event in the Caucasus mountains of 
> A young recruit, Darius Fisher, already an experienced explorer and eager to show his mettle, embarks on a journey to the mountains of eastern Romania.

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
