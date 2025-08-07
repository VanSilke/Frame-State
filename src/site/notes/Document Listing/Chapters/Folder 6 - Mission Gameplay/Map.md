---
{"dg-publish":true,"permalink":"/document-listing/chapters/folder-6-mission-gameplay/map/"}
---

The map describes where everything is situated, including but not limited to the pilot, their frame, NPCs and obstacles.

The map is separated into an even hexagonal column grid. The distance from one centre of the hex to the centre of another adjacent hex is equal 10 metres, and minor inconsistencies are ignored.
- Hexes are adjacent when connected by an edge. Hexes connected by only a corner are not adjacent.
- Mechanically, everything occupies space as close to the centre of its hex as possible. As such, the effective distance between things is always 10 metres, even if they are narratively "hugging" the adjacent edge.
# Points of Interest

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/designations/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




A designation, or a point of interest, is a mechanical device for describing any important map feature, including yourself, allies, enemies, and obstacles. A designation always occupies at least one hex. If multiple important things exist within the same hex, choose which one to designate.

Normally, you can only designate points of interest you can see.

</div></div>


# Hexes

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/hexes/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Hexes hold a number of variables, describing how they interact with the pilots, NPCs, projectiles and obstacles.


| Hex Variable | Description   |
| ------------ | ------------- |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Space\|Space]]    | 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/hexes-folder/space/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Technically hovering above the grid of some other hex, it is a 10-metre column of empty space. Space can be stacked indefinitely unless the map has some sort of ceiling. Most commonly used for flying.
- If you enter an air hex during ground movement, the movement ends and you begin to fall unless you flew.
- If you begin your turn in an air hex, you begin to fall.

</div></div>
    |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Occupied\|Occupied]] | 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/hexes-folder/occupied/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Holds any one Pilot, Frame, NPC, obstacle, or some large entity. Stops being occupied when the unit/entity moves out of the hex, or is destroyed enough to not count as obstacle anymore.
- Cannot be entered during movement.

</div></div>
 |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Terrain\|Terrain]]  | 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/hexes-folder/terrain/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Traversable, free of obstacles space on the "ground level", assigned a certain height.
- You cannot fall or move below a terrain hex.
- If the difference in height between adjacent terrain hexes is higher than 10 metres, you cannot enter the adjacent hex.

</div></div>
  |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Prop\|Prop]]     | 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/hexes-folder/prop/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Treated identically to a terrain hex, except it can be destroyed with enough effort, and can lie atop another hex type (typically terrain). 
- If a unit occupies a destroyed prop, it begins to fall.

Destructible props have a single value, from 1 upward. The value equals the prop's integrity, as well as all defences equally. The value is typically assigned by the handler.

</div></div>
     |


</div></div>


# Distances

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/distances/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Distances between points of interest always use the grid, starting from the hex occupied by the first point of interest, to a hex occupied by the second point of interest.
- In order to measure horizontal distance, begin from the first point's' hex, and move to the adjacent hex. Repeat this process until you reach the second point's hex. The shortest possible number of repeats that connects these in a path is the distance.
- In order to measure vertical distance, calculate the difference in elevation between the two points of interest, in 10-metre increments.
- In order to measure a three-dimensional distance, sum horizontal and vertical distances between the points of interest.

</div></div>

# Ranges

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/ranges/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




A range is the maximum possible distance, within which something can operate - be it the frame's movement, the weapon, and otherwise, measured from the origin point of the range (such as the frame's current position, or the epicentre of the explosion). 
- Hexes that cannot be reached within the maximum number of steps are effectively out of range.
- Normally ranges can be angled to avoid invalid hexes, for example when moving around an obstacle.
- Straight ranges cannot be angled. A point is out of straight range if you can't draw a straight, unobstructed line to it (handler being the final arbiter).

</div></div>

# Movement

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/movement/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




When something moves, its position on the grid changes. Normally this requires some sort of movement action, during which you draw distance to the hex you want to move into. This distance should respect movement range, if any.
- The path you take can be important if there are obstacles and hazards along the way.
- You can dynamically change the path you take as long as you keep moving, but once you stop moving or take another action, that particular movement is over.
- Moving into a hex is only possible if the hex is currently unoccupied.

</div></div>

# Sight

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-6-mission-gameplay/map-folder/sight/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Line of sight is a narrative concept describing what someone can and cannot see. If you cannot draw a relatively straight line from yourself to the point of interest, then it is out of your sight. You might still be able to discern that something is there, based on sound, environmental cues, and certain tests.
- Certain effects provide a highlight. This allows a pilot to maintain sight on the affected target even if no straight line of sight exists.

</div></div>
