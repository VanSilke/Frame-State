---
{"dg-publish":true,"permalink":"/other/playing-the-game/"}
---

Once you have [made your character](Making%20A%20Pilot), it is time to send them on a [mission](Missions). Before you sortie, however, it wouldn't hurt to undergo a number of voluntary training exercises.

# Gameplay Loop
The standard gameplay loop consists of [player pilots](Introduction) accepting [missions](Missions) from their [handler](Handling.md). Each [mission](Missions) consists of one or more [maps](Map), and each [map](Map) is composed of one or more [conflicts](Conflicts). Once a mission is complete, the [player pilots](Introduction) return to their narratively managed base of operations, where they enjoy the [mission's](Missions) [bounty](Credits) (reduced by the maintenance costs).

Note that both [player pilots](Introduction) and NPCs are [entities](Entities) of sort, and interact with each other similarly, with certain caveats.

# Activities
In order to interact with the game world, you dedicate your resources to performing [activities](Activities). 

| Activities    | Brief                                                                        |
| ------------- | ---------------------------------------------------------------------------- |
| [[Individual Files/Actions/Token Activities/Attack\|Attack]]    | [Use](Use) your [weapons](Weapons).                                          |
| [[Individual Files/Actions/Token Activities/Autofix\|Autofix]]   | Initiate [repair](Repair) using a [repair kit](Kits).                        |
| [[Individual Files/Actions/Token Activities/Fly\|Fly]]       | [Move in any way you like.](Movement)                                        |
| [[Individual Files/Actions/Token Activities/Move\|Move]]      | [Move, mostly horizontally.](Movement)                                       |
| [[Individual Files/Actions/Token Activities/Reload\|Reload]]    | Restore an [exhausted](Exhausted) [weapon](Weapons) to [ready](Ready) state. |
| [[Individual Files/Actions/Token Activities/Stabilise\|Stabilise]] | Initiate [stability](Stability) [recovery](Recovery).                        |
| [[Individual Files/Actions/Token Activities/Stance\|Stance]]    | [Weapon](Weapons) option for ignoring [recoil](Recoil).                      |
| [[Individual Files/Actions/Token Activities/Survey\|Survey]]    | Initiate [observation](Observe).                                             |

# Tests
Very often, you are required to make [tests](Tests), which involve throwing [dice](Numbers) and tallying up [values](Numbers). This is where your [frame's](Frame) design and  [character choices](Making%20A%20Pilot) come into play the most.

| Tests        | Brief                                                        |
| ------------ | ------------------------------------------------------------ |
| [[Individual Files/Actions/Tests/Mark Tests/Target\|Target]]   | Hit or miss your [designation](Designations).                |
| [[Individual Files/Actions/Tests/Opposition Tests/Brace\|Brace]]    | Reduce incoming [impact](Impact).                            |
| [[Individual Files/Actions/Tests/Opposition Tests/Correct\|Correct]]  | [Recover](Recovery) [stability](Stability).                  |
| [[Individual Files/Actions/Tests/Opposition Tests/Damage\|Damage]]   | Lower enemy [integrity](Integrity).                          |
| [[Individual Files/Actions/Tests/Opposition Tests/Defend\|Defend]]   | Reduce incoming [damage](Damage).                            |
| [[Individual Files/Actions/Tests/Opposition Tests/Evade\|Evade]]    | Avoid hostile [targeting](Target).                           |
| [[Individual Files/Actions/Tests/Opposition Tests/Impact\|Impact]]   | Build up [stagger](Staggered).                               |
| [[Individual Files/Actions/Tests/Opposition Tests/Observe\|Observe]]  | [Highlight](Highlighted) [things of interest](Designations). |
| [[Individual Files/Actions/Tests/Opposition Tests/Recharge\|Recharge]] | [Recover](Recovery) [energy](Energy). Done automatically.    |
| [[Individual Files/Actions/Tests/Opposition Tests/Repair\|Repair]]   | [Recover](Recovery) [integrity](Integrity).                  |

# Traversal
When [moving](Movement) through the [map](Map), you use both standard [movement](Move.md) and [flight](Fly.md), as well as gain (or are constrained by) traversal options based on your [legs](Legs) of choice. Your [line of sight](Sight) and [surveying](Survey.md) tests provide an image of the environment. The [map](Map) is separated into [hexes](Map), many of which count as [obstacles](Obstacles), which must be navigated around.