---
{"dg-publish":true,"permalink":"/document-listing/chapters/folder-1-first-steps/tests/"}
---

Whenever the Pilot attempts to do something dangerous (like do anything during combat) or interesting (as determined by the Handler), it becomes a test.

# Pilot Facing Tests
The tests are Pilot-facing at all times. This means, that Pilots always roll during a test, and NPCs (and other events described by the Handler) never do. Narratively, it is because of the players' competence that they persist through the challenges, and not because their foes fumbled.

The Pilot-facing nature of the system extends to almost all die rolls.

| Initiator | Test Type | Difference                                                    | On Draw |
| :-------: | :-------: | ------------------------------------------------------------- | ------- |
|   Pilot   | Proactive | When a Pilot hits the mark by 2 or more, they get a critical. | Hit     |
|  Handler  | Reactive  | When a Pilot misses the mark by 2 or more, they get a fumble. | Miss    |

| Term         | Brief                                       |
| ------------ | ------------------------------------------- |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Mark\|Mark]]     | The target number to hit with a score.      |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Score\|Score]]    | Sum of all modifiers and dice for the test. |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Ace\|Ace]]      | Event for rolling max on the die.           |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Critical\|Critical]] | Extreme success.                            |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Fumble\|Fumble]]   | Extreme failure.                            |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Hit\|Hit]]      | Success condition.                          |
| [[Document Listing/Chapters/Folder 1 - First Steps/Tests Folder/Miss\|Miss]]     | Failure condition.                          |

# Critical and Fumble
Both Critical and Fumble are dubbed Extreme outcomes. In most cases, an action or test lists only one outcome for "Extreme" category.
- When a Pilot gets a Critical, then the Extreme outcome likely concerns the Pilot.
- When a Pilot gets a Fumble, then the Extreme outcome likely concerns the other party.

For example, when a pilot gets targeted with an attack and fumbles, it is considered an Extreme outcome - but since the enemy is the one attacking, then it is the enemy who benefits and the Pilot who suffers a stronger hit.

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
# Special Considerations
There are several circumstances in which an NPC or external event can roll dice. This usually occurs if the Pilot has nothing to do with the event. For example, if an NPC unit overheats and must make a recovery check, it has little to do with the Pilot, so the Handler is permitted to roll for the NPC.
- If the Pilot player had a hand in forcing a test from the NPC, the Handler may permit the Pilot to "do the honours" and make the requisite roll.
- For low-importance enemies and events, the Handler may simply use an AVG outcome for the die used. This is most typical for combat, in which Pilots are expected to attack against static dodge, and dodge static attack.
- For high-importance enemies, the Handler may roll for the NPC to emphasise the foe's impact.