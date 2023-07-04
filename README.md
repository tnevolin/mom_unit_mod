# Master of magic normal unit balance mod

Attempt to modify normal unit stats to make them more sensible and usable.

_Disclaimer_

Master of magic is a great game of all times! 😀

# Intent

* Spread archetypical normal units strength proportionally so that each of them has an application in early-mid-late game.
* Adjust top level normal units to make sure they are about same strength/cost ratio and are strong enough to challenge tougher nodes/lairs.

# Problem statement

There are three major unit groups in the game: normal units, summoned units and heroes. Summoned units and heroes acceptably balanced to the level that they form their corresponding strategies. Whereas normal units generally suck except maybe some of them like paladins or slingers. There are few factors contributing to this.

* Normal units food upkeep burden is impossible at any stage of the game but most pronouncely at the beginning. Some average 5 size town can barely upkeep two spearmen garrison while it grows and advance infrastructure through two thirds of the game until it can support basic military. That is laughable.
* Normal archetipical units do not have good strength spread and do not have good middle strength unit representation. All these swordsmen, halebardiers, bowmen, shaman, cavalry units fall in about the same strength range and cost range. Player generally has no insentive to advance infrastructure to unlock next unit in line.
* A lot of high end normal units are pretty awfully balanced. Especially those 1-2 figure super unit requiring immense infrastructure investments may be worse than a middle tier one. Extreme example: Javeliners vs. Dragon Turtle. The latter is more costly and more difficult to achieve but is noticeably weaker. That again does not give player incentive to develop infrastructure. Thus shallowing game to pretty simple and repetitive play removing strategical advancement element from the game and making it much less replayable.

Which is sad.

😢

# Proposed solution

Reduce army food upkeep. CoM is already doing 1/2 food upkeep per unit.

Spread archetipical units more widely and evenly across strenght/cost scale giving player a meaningful strength/cost options. Each next level unit should be about 50% stronger than previous one. Also varying attack/defense balance could add variativety.

Adjust high end units in each race to make right infrastructure to strenght progression. Further investment into infrastructure should result in noticeably stronger units.

Adjust high end units to make them strong enough to be able to fight strongest lairs and nodes. In vanilla they are pretty incapable of that and a lot of strong lairs/nodes just stay sealed until the end of the game. Unless strong enough heroes can crack them, of course.

Adjust unit cost so that economy deprived races have them at relatively lower cost. Like lizardmen should have relatively strong but cheap units as this the only advantage they have.

# Races economical strength estimate

This is an attempt to estimate races economical strength to define racial unit cost coefficient. More economically advantageous race should have more expensive combat units.

These coefficients are on top of already balanced strength/cost within the race internally. For example, if Orcs cost coefficient is 1.00 and Dark Elves is 1.2, and two Orc spearmen equivalent in strength to one Dark Elf spearmen, then one Dark Elf spearmen cost is 1.2 of two Orc spearmen combined cost.

## Economical factors

Factors affecting production, population growth, expansion, mana etc. Essentially, everything that does not equates in unit combat strength. For example, Draconians fly is already factored into combat strength. However, it is also an expansion aid letting them reach out and expand quicker resulting in faster total population increase. Another example is Trolls regeneration. Again, it is already factored into combat strength. However, it is also has an effect of ressurecting fallen units after victory resulting in less unit building investments and faster growing army.

|factor|bonus|
|:----|----:|
|+20 growth|+1|
|+1 farmer food|+3|
|+1 worker production|+4|
|+50% gold|+4|
|+1/2 mana/pop|+1|
|missing Granary|-1|
|missing 4 buildings|-1|
|swimming units|+1|
|flying units|+2|
|regenerating units|+3|
|extra unrest|-2|

## Economy efficiency estimate (CoM)

|race|growth|ability|buildings|units|total|coefficient|
|:----|----:|----:|----:|----:|----:|----:|
|Orcs|0|0|0|0|0|1.0|
|Barbarians|0|0|-4|0|-4|1.4|
|Beastmen|-1|+1|0|0|0|1.0|
|Dark Elves|-2|+2|0|0|0|1.0|
|Draconians|-1|+1|-2|+2|0|1.0|
|Dwarves|-3|+10|-2|0|+5|0.8|
|Gnolls|-1|0|-3|0|-4|1.4|
|Halflings|-1|+3|-2|0|0|1.0|
|High Elves|-3|+1|-1|0|-3|1.3|
|High Men|-1|0|0|0|0|1.0|
|Klackons|+1|+8|-2|0|+5|0.8|
|Lizardmen|-1|0|-3|+1|-3|1.3|
|Nomads|0|+2|-2|0|0|1.0|
|Trolls|-1|0|-2|+3|0|1.0|

# Archetypical unit change

_This is comparing to vanilla. Some of these changes are similar to what CoM did._

Halberdiers are seriously stronger and better protected. They now take place between cavalry and pikemen. Rest of melee units is adjusted to be about proportinally distributed between spearmen and pikemen.

Bowmen, shaman, and normal magicians (except modified High Men and Dark Elves versions) are given extra ranged attack.

|type|melee|ranged|defense|
|:----|----:|----:|----:|
|spearmen|1||2|
|swordsmen|3||3|
|cavalry|5||2|
|halberdiers|6||4|
|pikemen|6||4|
|bowmen|1|2|1|
|shamans|2|3|3|
|priests|3|4|4|
|magicians|1|7|3|

