---
{"dg-publish":true,"permalink":"/document-listing/chapters/folder-6-mission-gameplay/map-folder/movement/"}
---

When something moves, its position on the grid changes. Normally this requires some sort of movement action, during which you draw distance to the hex you want to move into. This distance should respect movement range, if any.
- The path you take can be important if there are obstacles and hazards along the way.
- You can dynamically change the path you take as long as you keep moving, but once you stop moving or take another action, that particular movement is over.
- Moving into a hex is only possible if the hex is currently unoccupied.