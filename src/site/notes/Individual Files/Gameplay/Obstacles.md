---
{"dg-publish":true,"permalink":"/individual-files/gameplay/obstacles/"}
---

An obstacle is a variable within a [[Individual Files/Gameplay/Map\|hex]], which describes how it can interact with yourself, enemies, projectiles, etc.
* An [[Individual Files/Gameplay/Obstacles/Air\|air]] hex is a free hex above everything else.
* A [[Individual Files/Gameplay/Obstacles/Terrain\|terrain]] hex is the ground you walk on.
* A [[Individual Files/Gameplay/Obstacles/Prop\|prop]] hex is an object of interest, often destructible.

# Occupied Hexes
 An **occupied** hex is currently used by yourself, a friend, enemy, or another substantially large non-static entity. You cannot enter an occupied hex during [[Individual Files/Gameplay/Movement\|movement]]. An occupied hex always has one of the other hex types, and stops being occupied when you [[Individual Files/Gameplay/Movement\|move]] out of it in any way.