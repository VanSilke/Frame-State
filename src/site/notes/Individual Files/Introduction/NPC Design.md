---
{"dg-publish":true,"permalink":"/individual-files/introduction/npc-design/"}
---

When designing an NPC, focus on individual tests and statistics. 

An NPC is designed entirely separately from a [frame](Frame), but uses similar rules otherwise - an NPC needs to [target](Target) with its weapons, [evades](Evade) hostile attacks if it is able, and is subject to [integrity](Integrity.md) and [stability](Stability.md) rules. Generally, whenever a rule refers to "you" or a [frame](Frame), it can also apply to an NPC.
* The NPC has a differing base point buy relative to its category. This point buy can be adjusted ([handler's](Handling.md) choice) during the design process, but it should be reflected during [mission design](Handling.md).
* NPC entities are built with [values](Numbers), additively, instead of [dice](Numbers). 

| NPC Category | Base Points | Weapon Points | Weapon Limit | Skill Points |
| ------------ | ----------- | ------------- | ------------ | ------------ |
| SCV          | 5           | 5             | 5            | None         |
| LAD          | 10          | 10            | 6            | None         |
| HES          | 15          | 15            | 7            | 8            |
| Frame        | 20+         | 20+           | 8+           | 8+           |

**SCV**, or a Standard Combat Vehicle, is a typical armed machine used for warfare - the likes of tanks and attack helicopters. Compared to some other mechanized instruments of war, SCVs move too slowly or predictably to pose difficulty for any advanced targeting system. Further, a single square hit will destroy most SCVs.
* SCV has 3 base [integrity](Integrity) and [stability](Stability).
* SCV cannot [evade](Evade). All [targeting](Target) [tests](Tests) against a SCV are hits.
* SCV has no [energy](Energy) or [kits](Kits), and cannot increase these [statistics](Statistics).
* SCV has one [weapon](Weapons.md) of note.

**LAD**, or a Low-touch Autonomous Drone, is an autonomous machine. It features on-board artificial intelligence capable of making rudimentary decisions and following basic attack patterns. 
* LAD has 6 base [integrity](Integrity) and [stability](Stability).
* LAD has no [kits](Kits), and cannot increase this [statistic](Statistics).
* LAD has no [pilot skills](Skills) and cannot increase them.
* LAD has one [weapon](Weapons.md) of note.

A **HES**, or a High-touch Enhancement System, is a human-piloted advanced machine only a step below [frames](Frame).
* HES can have up to two [weapons](Weapons.md) of note.

A **frame**, which is not an acronym, is a machine that melds human skill with extraordinary military technology. It is usually humanoid, but other shapes also exist. Since each frame is mostly unique with very few examples of mass production, an encounter with hostile frames should be dangerous and memorable if possible.
