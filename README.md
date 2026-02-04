# Master of magic strategy balancing mod

Attempt to modify different aspects of the game to make them more usable.

# Normal units food support

## Problem

Super restrictive food support overshooting even gold support in its restrictivity. Player barely can maintain garrisons, especially at the beginning of the game. As the result, operating with large normal armies is unfeasible.

Another issue with food support is that exess of food is converted to gold at 2:1 ratio. And then this excess of gold is spent on rushing production at 2:1 ratio again. That is 4 (four!) times less efficient then simply adjusting worker allocation, which exchanges food to hammers at 1:1 ratio.
Obviously, with this system, player should try to minimize excessive food production doing micro adjustments _every time new unit produced_! Super annoying micromanagement.

## Solution

1. Change excess food to gold conversion ratio to 1:2 (one food to two gold). This way extra gold collected from excess food is sufficient to cover lost hammers and player does not need to adjust worker allocation too often.
2. Reduce food support to some fraction value (1/2, 1/4) or removing it altogether. Some players may still prefer to have it non zero to keep a "adjust worker allocation to feed the army" mini game as this is the only use of excess food production.

# Normal units balance

This is about normal units balance within race to let all of them play their role and to not shadow each other.

## Halberdiers

### Problem

melee units: Spearmen, Swordsmen, Cavalry, Halberdiers, Pikemen

All of the above are more or less efficient and in their place, except Cavalry and Halberdiers have more or less equal strength and there is a huge strength gap between Halberdiers and Pikemen.

Cavalry requires just two building to unlock and could be considered by cheap and light fast moving unit able to quickly close the gap to ranged units.

Halberdiers, from the other hand, require more buildings to unlock, but they feel pretty weak at this level. They should fill the gap of strong middle tier comparable to Pikemen.

### Solution

Beef up Halberdiers with +2 attack and +50% cost. This way they become a true usable heavy infantry of their era. They are still weaker than eight figures armor piercing Pikemen even with this improvement.

## Other arbitrary unit adjustments

Mostly changed unit cost for some overpowered ones. There are also few strength adjustments to balance racial/realm units with each other.

| unit | stats | cost | comment |
| ---- | ---- | ----: | ---- |
| Barbarian Bowmen | melee: 1 -> 2 |  | no racial thrown attack on this unit |
| Barbarian Berserkers |  | 300 | super strong |
| Beastmen Bowmen | ranged: 1 -> 2 |  | lacking +1 racial bonus on ranged |
| Beastmen Manticores | melee: 5 -> 8 |  | super weak for their tier |
| Dark Elf Spearmen |  | 40 | super powerful with their 8 figures ranged attack |
| Dark Elf Nightblades | melee: 4 -> 5 |  | too weak for their tier |
| Dark Elf Nightmares |  | 250 | strong |
| Draconian Air Ship |  | 400 | super strong |
| Dwarven Hammerhands |  | 250 | strong |
| Dwarven Golem | melee: 12 -> 16 | 300 | too weak for top tier |
| Gnoll	Bowmen | ranged: 1 -> 2 |  | compensation for racial extra attack |
| Halfling Slingers |  | 150 | strong |
| High Elf Longbowmen |  | 120 | strong |
| High Men Magicians |  | 200 | stronger than other magicians |
| High Men Pikemen |  | 120 | strong |
| High Men Paladins |  | 300 | strong |
| Klackon Stag Beetle |  | 250 | strong |
| Lizardman Shaman | defense: 3 -> 4 |  | designers missed to add +1 racial defense bonus to this one |
| Lizardman Dragon Turtle | melee: 10 -> 15, fire: 5 -> 10 | 200 | too weak for top tier |
| Nomad Horsebowmen |  | 100 | realively strong |
| Nomad Pikemen |  | 120 | strong |
| Nomad Rangers |  | 200 | strong |
| Nomad Griffins |  | 300 | strong |
| Orc Wyvern Riders | melee: 5 -> 8 | 300 | too weak for top tier |
| Troll	War Trolls |  | 250 | strong |
| Troll	War Mammoths | melee: 10 -> 12 | 400 | too weak for top tier |
| Chaos Chimera | melee: 7 -> 6, defense: 5 -> 3 |  | too strong 4 figures unit for its tier |
| Chaos	Doom Bat | melee: 10 -> 15 |  | super weak 1 figure unit |
| Chaos Efreet | melee: 9 -> 15 |  | strangely weak for its class |
| Chaos Hydra | hit points: 10 -> 5 |  | super strong 9 figures unit |
| Chaos Great Drake |  | 1500 | too strong for its price |
| Death Night Stalker | melee: 5 -> 10 |  | strangely weak even if invisible |

# Patches

| filename | effect |
| ---- | ---- |
| WFDGD20.TXT | Excess food to gold conversion ratio = 1:2 |
| WFDUPK05.TXT  | Units food support = 1/2 |
| WUNITS.TXT | Cumulative unit changes |
| WHEROES.TXT | Hero changes |

