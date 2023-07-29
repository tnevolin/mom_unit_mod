# Master of magic normal unit balance mod

Attempt to modify normal unit stats to make them more usable.

Modification is made on top of CoM. Therefore, a lot of CoM modifications were reverted or compensated to resemble vanilla development pace.

# Archetypical unit change

|type|melee|ranged|defense|
|:----|----:|----:|----:|
|spearmen|2||2|
|swordsmen|4||2|
|cavalry|5||2|
|halberdiers|6||4|
|bowmen|1|3|1|
|shamans|2|3|4|
|priests|3|4|4|
|magicians|1|5|3|

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
|High Elves|-3|+1|0|0|-2|1.2|
|High Men|-1|0|0|0|0|1.0|
|Klackons|+1|+8|-2|0|+5|0.8|
|Lizardmen|-1|0|-3|+1|-3|1.3|
|Nomads|0|+2|-2|0|0|1.0|
|Trolls|-1|0|-2|+3|0|1.0|

