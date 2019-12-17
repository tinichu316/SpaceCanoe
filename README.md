# SpaceCanoe
##### A Game by William Wang
## November 15, 2019: The Combat Update
* Improved, more reliable, dnd-style combat revamp
* More complex encounters
* More ship upgrades with a greater emphasis on consistent combat
* UI improvements
* QOL improvements (skipping rolls)
* Re-factored entire encounter/dice system
* And many, many bug fixes.

## Introduction
Space canoe is a survival, resource management game about exploring the high seas and the cosmos to reach the center of the galaxy. Along your way, you will need to strategically delegate your crew to gathering and maintaining your food, water, and morale resources in order to survive your journey.

At each step of the way you will face a random encounter that could determine whether you and your crew make it past the next stage.

## Development
Space canoe features a robust encounter system, an upgrades system, as well as a DnD inspired resource and combat system. Inspiration was also taken from games such as Gods Will be Watching, Oregon Trail, and FTL.

The game is currently fully playable and features over 50 custom encounters. It was developed in Unity using C# slowly over the course of a month and repeatedly updated and balanced based on playtesting feedback. It was then revisited a year later in 2019 to overhaul the combat system, add new encounters, and completely refactor and restructure the way encounters were handled.

Currently, as of December 2019, the game is in Beta. Updates in the near future would be minor balance tweaks or new encounters.

## Future Updates
Near-future updates include ambient BGM and standardized combat encounters. Future updates include more UI polishing, further game balancing, encounter tweaking and creating procedural encounter generators.

Far-future updates include individualized crew members with certain skills towards gathering certain resources or combat boosts, choose-able encounter paths rather than a linear story, and a more strategic combat system.

If you have any feedback on UI/Balance/Gameplay or any suggestions for new encounters, please do not hesitate to contact me and we will work on getting it in the game.

## Mechanics
Each turn, you will lose food and water equal to the number of crew, as well as some morale. If you do not have enough resources, you will instead lose morale equal to the food or water you would have lost.

At 0 morale, you start to lose increasing amounts of health per turn.

Allocate your crew members to each of the many resource modules.

"nd6" means you roll a 6 sided die [# of crew assigned] times and take the total. I.e. the results for 1 crew are 1d6 so 1, 2, 3, 4, 5, or 6.

Earn scrap through risky scavenging or through random encounters and spend it on ship upgrades and repairs in the "Upgrades" panel. Your attack/defense die and your damage dice can be upgraded either to increase its power (maximum roll), or its bonus to roll.

In combat, you and your opponent both roll an attack die, d20, as well as a defense die, d10 and add your respective attack and defense bonuses. You can choose to change your stance to gain a small bonus to either your attack or defense. If your damage roll is greater or equal to your opponent's defense roll (and vice versa), you get to roll your damage dice to deal damage.

Your damage dice will gain exp each turn as well as through combat. Upon acquiring enough exp, the dice will rank up to 3 times, each time gaining additional bonuses.
