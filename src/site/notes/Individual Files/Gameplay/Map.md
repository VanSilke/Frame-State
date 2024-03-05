---
{"dg-publish":true,"permalink":"/individual-files/gameplay/map/"}
---

The map describes where everything is situated, including but not limited to yourself, enemies and [obstacles](Obstacles.md).

The map is separated into an even hexagonal column grid. The distance from one centre of the hex to the centre of another adjacent hex is roughly 10 metres, horizontally and vertically.

# Distances
Distances are measured from a point of interest (either enemy, friend or some object) to another point of interest (such as yourself).
1. First, choose a point of origin. This is a hex in which the object of interest resides. Then, choose a target hex.
2. Begin from the point of origin, and advance to an adjacent hex. Repeat until you have reached the target hex. The absolute minimum amount of repeats is the distance.
3. If the point of interest has a different elevation, the distance is increased by the difference in elevation between the point of origin to the target hex.

# Ranges
Ranges are the maximum distance. In other words, when you measure a distance, you may only repeat Step 2. as many times as the range number. If you cannot reach the target hex within this limit, that target hex is out of range. This is helpful when determining whether an enemy can be harmed by your weapons, or if something is within the explosion radius.
* Normal ranges can be angled, which means you can advance to any adjacent hex during Step 2. This allows you to reach a target hex that is behind an obstacle, for example.
* Straight ranges cannot be angled, which means you can only advance to an adjacent hex during Step 2. if it roughly follows the same direction (handler's choice). If you can't draw a straight line from origin to target hex, you are effectively out of range.