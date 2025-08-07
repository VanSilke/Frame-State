---
{"dg-publish":true,"permalink":"/document-listing/chapters/folder-6-mission-gameplay/map-folder/hexes/"}
---

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
