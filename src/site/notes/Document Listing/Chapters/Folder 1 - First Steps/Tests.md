---
{"dg-publish":true,"permalink":"/document-listing/chapters/folder-1-first-steps/tests/"}
---

Whenever the Pilot attempts to do something dangerous (like do anything during combat) or interesting (as determined by the Handler), it becomes a test.

# Pilot Facing Tests
The tests are Pilot-facing at all times. This means, that Pilots always roll during a test, and NPCs (and other events described by the Handler) never do. Narratively, it is because of the players' competence that they persist through the challenges, and not because their foes fumbled.



| Term | Brief     |
| ---- | --------- |
| Mark | 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/document-listing/chapters/folder-1-first-steps/tests-folder/mark/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




A mark is a test value set by the Handler.
- If your score is above this value, you "hit the mark", otherwise you "miss the mark", with variable outcome on a draw and extreme outcome on a critical or fumble.

</div></div>
 |




| Initiator | Test Type | Difference                                                    | On Draw |
| :-------: | :-------: | ------------------------------------------------------------- | ------- |
|   Pilot   | Proactive | When a Pilot hits the mark by 2 or more, they get a critical. | Hit     |
|  Handler  | Reactive  | When a Pilot misses the mark by 2 or more, they get a fumble. | Miss    |



| Term         | Brief |
| ------------ | ----- |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Mark\|Mark]]     |       |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Score\|Score]]    |       |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Ace\|Ace]]      |       |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Critical\|Critical]] |       |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Fumble\|Fumble]]   |       |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Hit\|Hit]]      |       |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Miss\|Miss]]     |       |



# Structuring Tests
The goal of any one test is to generate a score and compare it against a mark.

A test consists of dice, modifiers, and a mark. The test specifies which dice and modifiers are used. Specific rules may modify this structure.


| **Score Calculation** |
|:---:|
| Score = Dice + Modifiers |

All tests follow this basic resolution sequence, divided into stages.
1. Roll all dice used in the test.
	- Keep only the highest result, discarding all others.
	- On an ace, add a modifier of 2 to the next stage. 
	- Any used die can ace, but only one ace counts.
2. Sum all modifiers used in the test.
3. Generate a score by summing results from stages 1 and 2.
4. Compare the score to the test's mark.
5. Check the resolution table. It should be easy to internalize after a couple viewings.

|    Score vs Mark    | Proactive Tests | Reactive Tests |
| :-----------------: | :-------------: | :------------: |
| Lower by 2 or less  |      Miss       |     Fumble     |
|        Lower        |      Miss       |      Miss      |
|        Draw         |       Hit       |      Miss      |
|       Higher        |       Hit       |      Hit       |
| Higher by 2 or less |    Critical     |      Hit       |
