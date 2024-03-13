---
{"dg-publish":true,"permalink":"/individual-files/gameplay/obstacles/prop/"}
---

A prop hex is the same as terrain hex, except it can be destroyed with enough effort and has another type of hex below it. 

The amount of effort necessary to destroy a prop hex is variable per prop, and mostly left up to the handler if not specified. If you are occupying a prop that is destroyed, you begin to [[Individual Files/Gameplay/Falling\|fall]]. Props specify whether you can [[Individual Files/Gameplay/Movement\|move vertically]] below them.

In order to design a destructible prop, assign a single value to [[Individual Files/Character Generation/Frame/Frame Statistics/Integrity\|integrity]] and [[Individual Files/Actions/Tests/Opposition Tests/Defend\|defences]] which are applied universally against all [[Individual Files/Character Generation/Weapons/Damage Type\|damage types]]. A prop cannot [[Individual Files/Actions/Tests/Opposition Tests/Evade\|evade]].

| Value | Example           |
| ----- | ----------------- |
| 0     | Shack, tree patch |
| 1     | Rubble            |
| 2     | Building          |
| 3     | Reinf. Building   |
| 4     | Stone wall        |
| 5     | Stone Reinf. Wall |
| 6     | Metal Pillar      |
| 7     | Solid Metal Wall  |
