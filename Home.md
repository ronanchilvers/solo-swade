---
created: 2023-07-07 11:29
banner: "![[home-2.jpg]]"
banner_y: 0.77
banner_lock: true
---


> [!abstract] Starting Scene
> ![[fate-rpg.png|right|300]]
> While many western countries are excited about the new researches into electro-arcane energy, there are those who fear its power. They fear that we don't yet understand the true source of the newly discovered powers. They fear that it may not be what it seems and that we are on the brink of calamity.
> The Society of Curious Personages is a group of skeptics formed in London in 1928, which aims to discover the truth. Word has reached London of a strange event high in the Austrian Alps. A monitoring station in Geneva (?) detected an enormous power surge centred close to a small town named Kruezberg. At the same time, one of the Society's assets in the region was travelling in the area and reported a huge shockwave rippling through the town - windows shattered and lightning forked the sky.
> Darius Fisher, already an experienced explorer. a member of the Society and eager for adventure, leaves London on the express train bound for Dover. He is booked on the overnight boat to Ostend and from there he takes the overnight train bound for the Tyrollean capital of Innsbruck. From there he heads east into the Tyrollean Alps, to the small town of Kruezberg.

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
