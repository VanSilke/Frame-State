---
{"dg-publish":true,"permalink":"/individual-files/gameplay/obstacles/prop/"}
---

A prop hex is the same as terrain hex, except it can be destroyed with enough effort and has another type of hex below it. 

The amount of effort necessary to destroy a prop hex is variable per prop, and mostly left up to the handler if not specified. If you are occupying a prop that is destroyed, you begin to [fall](Falling.md). Props specify whether you can [move vertically](Movement.md) below them.

In order to design a destructible prop, assign a single value to [integrity](Integrity.md) and [defence](Defend.md) which is applied universally against all [damage types](Damage%20Type.md). A prop has no [evasion](Evade.md) [score](Score.md) or [stability](Stability.md). 

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
