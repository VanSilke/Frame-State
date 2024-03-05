---
{"dg-publish":true,"permalink":"/individual-files/gameplay/rounds/"}
---

A round is separated into a number of segments. You always begin a [conflict](Conflicts) with a friendly segment, unless it’s an ambush.

[Player](Introduction) decide among each other who wants to act when within the friendly segment. [NPCs](Entities.md) controlled by the [handler](Handling.md) act according to the [handler's](Handling.md) decisions, but their disposition slots them into a specific overarching segment order.

# Taking Your Turn
1. Apply events that occur at the beginning of your turn.
2. Perform [activities](Activities.md) you can think of within reason, until all resources or options have been exhausted. You may declare to end your turn early to preserve resources or if you don't need to move.
3. Apply events that occur at the end of your turn.
4. Choose the next [entity](Entities.md) to take its turn next. Repeat with step 1. as that new [entity](Entities.md), until all have taken their turns.
5. Move on to the next segment.

# Round Segments
A round is separated into segments.
1. During a **friendly** turn, you and your fellow [player pilots](Entities.md) take your activities.
2. During an **ally** turn, [NPCs](Entities.md) take their activities and autonomous friendly events occur.
3. During a **neutral** turn, [NPCs](Entities.md) on neither side of the conflict take their activities.
4. During an **enemy** turn, [NPCs](Entities.md) hostile to the player pilots take their activities.
5. During an **environmental** turn, the environmental effects occur. This includes [falling](Falling.md) from an [air](Air.md) [hex](Map.md).
