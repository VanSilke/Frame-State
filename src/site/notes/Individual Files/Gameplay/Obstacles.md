---
{"dg-publish":true,"permalink":"/individual-files/gameplay/obstacles/"}
---

An obstacle is a variable within a [hex](Map.md), which describes how it can interact with yourself, enemies, projectiles, etc.
* An [air](Air.md) hex is a free hex above everything else.
* A [terrain](Terrain.md) hex is the ground you walk on.
* A [prop](Prop.md) hex is an often destrictible object of interest.

# Occupied Hexes
 An **occupied** hex is currently used by yourself, a friend, enemy, or another substantially large non-static entity. You cannot enter an occupied hex during [movement](Movement.md). An occupied hex always has one of the other hex types, and stops being occupied when you [move](Movement.md) out of it in any way.