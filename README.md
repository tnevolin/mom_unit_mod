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

# Heroes

## Problem

1. They are useless and fragile at the beginning. Player has to include them into combat but just let them sit and learn.
2. Some abilities (Agility, Blademaster) turn even low level heroes into superpower machines.
3. Due to steep hero progression, players usually refuse to replace their low level experienced heroes with higher level recruits.
4. Due to their fragility they are destroyed pretty quickly by direct damage attacks and spells. That requires constant attention on keeping them alive.

## Solution

Beef up some weaker and lower level heroes (+HP and other stats) to make them less fragile and more useful from the beginning. Flat addition should not sqew up their advanced versions.

1. Recruited heroes are less fragile and can fight in battle on par with normal units.
2. Some rebalancing between heroes.
3. Experienced heroes are _slightly_ more tough and better. They will die less frequent and player should not pay extra attention on protecting them.
4. With lower dying chances it should be fine to allow them to rotate even when they do die.


| unit | HP | me | ra | de | comment |
| ---- | ----: | ----: | ----: | ----: | ---- |
| Dwarf | +5 | +2 |  | +1 | rather plain hero |
| Barbarian | +5 |  |  |  |  |
| Sage | +5 |  |  |  |  |
| Dervish | +5 |  |  |  |  |
| Beastmaster | +5 | +4 |  | +1 | surprisingly useless and unadvanceable guy even for the lowest level |
| Bard | +5 | +2 |  | +1 | too weak even with Leadership |
| Orc Warrior | +5 |  |  |  |  |
| Healer | +5 |  |  |  |  |
| Huntress | +5 |  |  |  |  |
| Thief | +3 | +2 |  |  | limited HP boost due to Agility |
| Druid | +5 |  |  |  |  |
| War Monk | +2 |  |  |  | limited HP boost due to super Agility |
| Warrior Mage | +5 |  |  |  |  |
| Magician | +5 |  | -4 |  | too devastating ranged attack with Arcane Power at this tier |
| Assassin | +5 | +2 |  |  | too low melee to benefit from Blademaster |
| Wind Mage | +5 |  |  |  |  |
| Ranger | +5 |  |  |  | Might is not well placed in this hero, but I do not know what to do with him now |
| Draconian | +5 |  |  |  |  |
| Witch | +5 |  |  |  |  |
| Golden One | +5 |  |  |  |  |
| Ninja | +2 | +2 |  |  | limited HP boost due to invisibility |
| Rogue | +5 |  |  |  |  |
| Amazon | +5 |  |  |  |  |
| Warlock | +5 |  |  |  |  |
| Unknown | +5 |  |  |  |  |
| Illusionist | +5 |  |  |  |  |
| Swordsman | +5 |  |  |  |  |
| Priestess | +5 |  |  |  |  |
| Paladin | +5 |  |  |  |  |
| Black Knight | +5 |  |  |  |  |
| Elven Archer | +5 |  | -2 |  | insanely powerful shooter with Blademaster |
| Knight | +5 |  |  |  |  |
| Necromancer | +5 |  |  |  |  |
| Chaos Warrior | +5 | -4 | -4 |  | insanely powerful combat machine with Arcane Power and Armor Piercing |
| Chosen |  |  |  |  | no boost needed at all |

# Patches

| filename | effect |
| ---- | ---- |
| WFDGD20.TXT | Excess food to gold conversion ratio = 1:2 |
| WFDUPK05.TXT  | Units food support = 1/2 |
| WUNITS.TXT | Cumulative unit changes |
| WHEROES.TXT | Hero changes |

