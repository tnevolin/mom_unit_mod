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

Reduce army food upkeep. Currently I am trying 1/2 food upkeep per unit. Could be still high. May also try 1/4.

Spread archetipical units more widely and evenly across strenght/cost scale giving player a meaningful strength/cost options. Each next level unit should be about 50% stronger than previous one. Also varying attack/defense balance could add variativety.

Adjust high end units in each race to make right infrastructure to strenght progression. Further investment into infrastructure should result in noticeably stronger units.

Adjust high end units to make them strong enough to be able to fight strongest lairs and nodes. In vanilla they are pretty incapable of that and a lot of strong lairs/nodes just stay sealed until the end of the game. Unless strong enough heroes can crack them, of course.

Adjust unit cost so that economy deprived races have them at relatively lower cost. Like lizardmen should have relatively strong but cheap units as this the only advantage they have.

# Races economical strength estimate

This is an attempt to estimate races economical strength to define average unit combat efficiency (strength / cost). More economically advantageous race should have less effective combat units. By economy here I understand all factors contributing to combined production development: production bonuses, food bonuses, gold bonuses, mana bonuses, allowed buildings, etc.

These coefficients are on top of already balanced strength/cost within the race internally. For example, if Orcs cost efficiency coefficient is 1.00 and Dark Elves is 0.9, and two Orc spearmen equivalent in strength to one Darl Elf spearmen, then two Orc spearmen combined cost will be 0.9 of one Dark Elf spearmen cost.

## Unit cost efficiency coefficients

|race|economics|coefficient|factors|
|:----|----:|----:|:----|
|Orcs|average|1.0|Used as a baseline. Can build all economical buildings, no bonuses.|
|Barbarians|average|1.0|fast growth (+1), lack some buildings (-1)|
|Beastmen|average|1.0|0.5 mana (+1), lack some buildings (-1)|
|Dark Elves|stronger|0.8|1.0 mana (+2), slow growth (-1)|
|Draconians|stronger|0.8|0.5 mana (+1), fast expansion (+1)|
|Dwarves|strong|0.6|0.5 mana (+1), prod/gold bonus (+5), slow growth (-1), lack of buildings (-1)|
|Gnolls|weak|1.6|impared economy (-3)|
|Halflings|stronger|0.8|food bonus (+3), bad economy (-2)|
|High Elves|average|1.0|0.5 mana (+1), slow growth (-1)|
|High Men|average|1.0|Similar to Orcs economy|
|Klackons|average|1.0|prod bonus (+3), impared economy (-3)|
|Lizardmen|weakest|2.0|appaling economy (-4)|
|Nomads|average|1.0|gold bonus (+1)|
|Trolls|average|1.0|regeneration (+3), slow growth (-1), impared economy (-3)|

# Archetypical unit change

Halberdiers becomes seriously stronger and well protected. Rest of melee units is adjusted to be about proportinally distributed between spearmen and pikemen.

Bowmen and shaman are increased in strength. Priests melee is slightly reduced. They are now more proportionally distributed on bowmen - magician scale.

Magicians are given extra attack. This is applicable to all non modified archetypical magicians (except Dark Elves and High Men ones).

|type|melee|ranged|defense|
|:----|----:|----:|----:|
|spearmen|1||2|
|swordsmen|4||2|
|cavalry|5||2|
|halberdiers|7||4|
|pikemen|7||4|
|bowmen|1|2|1|
|shamans|2|3|3|
|priests|2|4|4|
|magicians|1|6|3|

