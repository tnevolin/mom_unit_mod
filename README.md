# Master of magic strategy balancing mod

Attempt to modify different aspects of the game to make them more usable.

# Normal units food support

<ins>Problem</ins>

Super restrictive food support overshooting even gold support in its restrictivity. Player barely can maintain garrisons, especially at the beginning of the game. As the result, operating with large normal armies is unfeasible.

Another issue with food support is that exess of food is converted to gold at 2:1 ratio. And then this excess of gold is spent on rushing production at 2:1 ratio again. That is 4 (four!) times less efficient then simply adjusting worker allocation, which exchanges food to hammers at 1:1 ratio.
Obviously, with this system, player should try to minimize excessive food production doing micro adjustments _every time new unit produced_! Super annoying micromanagement.

 <ins>Solution</ins>

1. Change excess food to gold conversion ratio to 1:2 (one food to two gold). This way extra gold collected from excess food is sufficient to cover lost hammers and player does not need to adjust worker allocation too often.
2. Reduce food support to some fraction value (1/2, 1/4) or removing it altogether. Some players may still prefer to have it non zero to keep a "adjust worker allocation to feed the army" mini game as this is the only use of excess food production.

# Units

## General rules

1. There should be no duplicate racial/realm units. They should differ either in type (melee/ranged/flying) or in strength.
2. Higher tier unit should be stronger and proportionally expensive.
3. Small adjustment between units of similar class to highlight less used one (War Bears).

## Specific issues

### Halberdiers

<ins>Problem</ins>

melee units: Spearmen, Swordsmen, Cavalry, Halberdiers, Pikemen

All of the above are more or less efficient and in their place, except Cavalry and Halberdiers have more or less equal strength and there is a huge strength gap between Halberdiers and Pikemen.

Cavalry requires just two building to unlock and could be considered as cheap and light fast moving unit able to quickly close the gap to ranged units.

Halberdiers, from the other hand, require more buildings to unlock, but they feel pretty weak at this level. They should fill the gap of strong middle tier comparable to Pikemen.

<ins>Solution</ins>

Beef up Halberdiers with +2 attack and +50% cost. This way they become a true usable heavy infantry of their era. They are still weaker than eight figures armor piercing Pikemen even with this improvement.

### Heroes

<ins>Problem</ins>

1. They are useless and fragile at the beginning. Player has to include them into combat but just let them sit and learn.
2. Some abilities (Agility, Blademaster) turn even low level heroes into superpower machines.
3. Due to steep hero progression, players usually refuse to replace their low level experienced heroes with higher level recruits.
4. Due to their fragility they are destroyed pretty quickly by direct damage attacks and spells. That requires constant attention on keeping them alive.

<ins>Solution</ins>

Beef up some weaker and lower level heroes (+HP and other stats) to make them less fragile and more useful from the beginning. Flat addition should not sqew up their advanced versions.

1. Recruited heroes are less fragile and can fight in battle on par with normal units.
2. Some rebalancing between heroes.
3. Experienced heroes are _slightly_ more tougher and better. They will die less frequent and player should not pay extra attention on protecting them.
4. With lower dying chances it should be fine to allow them to rotate even when they do die.

## Summary table

| # | race | name | me | ra | de | HP | cost | comment |
| ----: | ---- | ---- | ----: | ----: | ----: | ----: | ----: | ---- |
| 0 | Dwarven | Dwarf | 8 |  | 5 | 15 |  | not too advanceable |
| 1 | Barbarian | Barbarian |  |  |  | 14 |  |  |
| 2 | High Men | Sage |  |  |  | 10 |  |  |
| 3 | High Men | Dervish |  |  |  | 11 |  |  |
| 4 | Beastmen | Beastmaster | 10 |  | 7 | 12 |  | absolutely unadvanceable guy |
| 5 | High Men | Bard | 7 |  | 7 | 11 |  | too weak even with Leadership |
| 6 | Orc | Orc Warrior |  |  |  | 13 |  |  |
| 7 | High Men | Healer |  |  |  | 10 |  |  |
| 8 | High Men | Huntress |  |  |  | 12 |  |  |
| 9 | High Men | Thief | 7 |  |  | 12 |  | too toothless |
| 10 | High Men | Druid |  |  |  | 10 |  |  |
| 11 | High Men | War Monk |  |  |  | 11 |  |  |
| 12 | High Men | Warrior Mage |  |  |  | 12 |  |  |
| 13 | High Men | Magician |  | 4 |  | 10 |  | extremenly OP with Arcane Power |
| 14 | High Men | Assassin | 7 |  |  | 11 |  | not enough melee to utilize Blademaster |
| 15 | High Men | Wind Mage |  |  |  | 10 |  |  |
| 16 | High Men | Ranger |  |  |  | 13 |  |  |
| 17 | Draconian | Draconian |  |  |  | 13 |  |  |
| 18 | High Men | Witch |  |  |  | 10 |  |  |
| 19 | High Men | Golden One |  |  |  | 11 |  |  |
| 20 | High Men | Ninja | 8 |  |  | 12 |  | not too strong even with invisibility |
| 21 | High Men | Rogue | 10 |  | 7 | 13 |  | too weak for its tier |
| 22 | High Men | Amazon | 5 |  |  |  |  | too strong with Might and Blademaster |
| 23 | High Men | Warlock |  |  |  | 10 |  |  |
| 24 | High Men | Unknown |  |  |  | 13 |  |  |
| 25 | High Men | Illusionist |  |  |  | 10 |  |  |
| 26 | High Men | Swordsman |  |  |  | 15 |  |  |
| 27 | High Men | Priestess |  |  |  | 10 |  |  |
| 28 | High Men | Paladin |  |  |  | 13 |  |  |
| 29 | High Men | Black Knight |  |  |  |  |  |  |
| 30 | High Elf | Elven Archer | 3 | 6 |  | 11 |  | OP with original build |
| 31 | High Men | Knight | 10 |  | 7 | 14 |  | insufficiently strong for this tier |
| 32 | High Men | Necromancer |  |  |  | 10 |  |  |
| 33 | High Men | Chaos Warrior | 4 | 4 |  |  |  | insanely OP with Arcane Power and Armor Piercing |
| 34 | Life | Chosen | 8 |  | 6 |  |  | a living tank with original build |
| 35 | Generic | Trireme |  |  |  |  |  |  |
| 36 | Generic | Galley |  |  |  |  |  |  |
| 37 | Generic | Catapult |  |  |  |  |  |  |
| 38 | Generic | Warship |  |  |  |  | 300 |  |
| 39 | Barbarian | Spearmen |  |  |  |  |  |  |
| 40 | Barbarian | Swordsmen |  |  |  |  |  |  |
| 41 | Barbarian | Bowmen |  |  |  |  |  |  |
| 42 | Barbarian | Cavalry |  |  |  |  |  |  |
| 43 | Barbarian | Shaman |  |  |  |  |  |  |
| 44 | Barbarian | Settlers |  |  |  |  |  |  |
| 45 | Barbarian | Berserkers |  |  |  |  | 300 |  |
| 46 | Beastmen | Spearmen |  |  |  |  |  |  |
| 47 | Beastmen | Swordsmen |  |  |  |  |  |  |
| 48 | Beastmen | Halberdiers | 7 |  |  |  | 120 |  |
| 49 | Beastmen | Bowmen |  |  |  |  |  |  |
| 50 | Beastmen | Priests |  |  |  |  |  |  |
| 51 | Beastmen | Magicians |  |  |  |  |  |  |
| 52 | Beastmen | Engineers |  |  |  |  |  |  |
| 53 | Beastmen | Settlers |  |  |  |  |  |  |
| 54 | Beastmen | Centaurs |  |  |  |  |  |  |
| 55 | Beastmen | Manticores | 8 |  | 4 |  |  |  |
| 56 | Beastmen | Minotaurs |  |  |  |  | 350 |  |
| 57 | Dark Elf | Spearmen |  |  |  |  | 40 |  |
| 58 | Dark Elf | Swordsmen |  |  |  |  |  |  |
| 59 | Dark Elf | Halberdiers | 6 |  |  |  | 150 |  |
| 60 | Dark Elf | Cavalry |  |  |  |  |  |  |
| 61 | Dark Elf | Priests |  |  |  |  |  |  |
| 62 | Dark Elf | Settlers |  |  |  |  |  |  |
| 63 | Dark Elf | Nightblades | 5 |  |  |  |  |  |
| 64 | Dark Elf | Warlocks |  |  |  |  |  |  |
| 65 | Dark Elf | Nightmares |  |  |  |  | 300 |  |
| 66 | Draconian | Spearmen |  |  |  |  |  |  |
| 67 | Draconian | Swordsmen |  |  |  |  |  |  |
| 68 | Draconian | Halberdiers | 6 |  |  |  | 150 |  |
| 69 | Draconian | Bowmen |  |  |  |  |  |  |
| 70 | Draconian | Shaman |  |  |  |  |  |  |
| 71 | Draconian | Magicians |  |  |  |  |  |  |
| 72 | Draconian | Engineers |  |  |  |  |  |  |
| 73 | Draconian | Settlers |  |  |  |  |  |  |
| 74 | Draconian | Doom Drakes |  |  |  |  |  |  |
| 75 | Draconian | Air Ship |  |  |  |  | 500 |  |
| 76 | Dwarven | Swordsmen |  |  |  |  |  |  |
| 77 | Dwarven | Halberdiers | 6 |  |  |  | 150 |  |
| 78 | Dwarven | Engineers |  |  |  |  |  |  |
| 79 | Dwarven | Hammerhands |  |  |  |  | 350 |  |
| 80 | Dwarven | Steam Cannon |  |  |  |  |  |  |
| 81 | Dwarven | Golem | 20 |  | 10 |  | 500 | they should have some serious punch for top tier unit |
| 82 | Dwarven | Settlers |  |  |  |  |  |  |
| 83 | Gnoll | Spearmen |  |  |  |  |  |  |
| 84 | Gnoll | Swordsmen |  |  |  |  |  |  |
| 85 | Gnoll | Halberdiers | 8 |  |  |  | 60 |  |
| 86 | Gnoll | Bowmen |  |  |  |  |  |  |
| 87 | Gnoll | Settlers |  |  |  |  |  |  |
| 88 | Gnoll | Wolf Riders |  |  |  |  | 150 |  |
| 89 | Halfling | Spearmen |  |  |  |  |  |  |
| 90 | Halfling | Swordsmen |  |  |  |  |  |  |
| 91 | Halfling | Bowmen |  |  |  |  |  |  |
| 92 | Halfling | Shaman |  |  |  |  |  |  |
| 93 | Halfling | Settlers |  |  |  |  |  |  |
| 94 | Halfling | Slingers |  |  |  |  | 150 |  |
| 95 | High Elf | Spearmen |  |  |  |  |  |  |
| 96 | High Elf | Swordsmen |  |  |  |  |  |  |
| 97 | High Elf | Halberdiers | 6 |  |  |  | 100 |  |
| 98 | High Elf | Cavalry |  |  |  |  |  |  |
| 99 | High Elf | Magicians |  |  |  |  |  |  |
| 100 | High Elf | Settlers |  |  |  |  |  |  |
| 101 | High Elf | Longbowmen |  |  |  |  | 120 |  |
| 102 | High Elf | Elven Lords |  |  |  |  |  |  |
| 103 | High Elf | Pegasai |  |  |  |  |  |  |
| 104 | High Men | Spearmen |  |  |  |  |  |  |
| 105 | High Men | Swordsmen |  |  |  |  |  |  |
| 106 | High Men | Bowmen |  |  |  |  |  |  |
| 107 | High Men | Cavalry |  |  |  |  |  |  |
| 108 | High Men | Priests |  |  |  |  |  |  |
| 109 | High Men | Magicians |  |  |  |  | 200 |  |
| 110 | High Men | Engineers |  |  |  |  |  |  |
| 111 | High Men | Settlers |  |  |  |  |  |  |
| 112 | High Men | Pikemen |  |  |  |  | 120 |  |
| 113 | High Men | Paladins |  |  |  |  | 300 |  |
| 114 | Klackon | Spearmen |  |  |  |  |  |  |
| 115 | Klackon | Swordsmen |  |  |  |  |  |  |
| 116 | Klackon | Halberdiers | 6 |  |  |  | 120 |  |
| 117 | Klackon | Engineers |  |  |  |  |  |  |
| 118 | Klackon | Settlers |  |  |  |  |  |  |
| 119 | Klackon | Stag Beetle |  |  |  |  | 300 |  |
| 120 | Lizardman | Spearmen |  |  |  |  |  |  |
| 121 | Lizardman | Swordsmen |  |  |  |  |  |  |
| 122 | Lizardman | Halberdiers | 6 |  |  |  | 60 |  |
| 123 | Lizardman | Javelineers |  |  |  |  | 120 |  |
| 124 | Lizardman | Shaman |  |  | 4 |  |  | missing racial defense bonus |
| 125 | Lizardman | Settlers |  |  |  |  |  |  |
| 126 | Lizardman | Dragon Turtle | 15 | 10 |  |  | 150 | should have more advanced unit for this tier |
| 127 | Nomad | Spearmen |  |  |  |  |  |  |
| 128 | Nomad | Swordsmen |  |  |  |  |  |  |
| 129 | Nomad | Bowmen |  |  |  |  |  |  |
| 130 | Nomad | Priests |  |  |  |  |  |  |
| 131 | Nomad | Magicians |  |  |  |  |  |  |
| 132 | Nomad | Settlers |  |  |  |  |  |  |
| 133 | Nomad | Horsebowmen |  |  |  |  | 100 |  |
| 134 | Nomad | Pikemen |  |  |  |  | 120 |  |
| 135 | Nomad | Rangers |  |  |  |  | 200 |  |
| 136 | Nomad | Griffins |  |  |  |  | 300 |  |
| 137 | Orc | Spearmen |  |  |  |  |  |  |
| 138 | Orc | Swordsmen |  |  |  |  |  |  |
| 139 | Orc | Halberdiers | 6 |  |  |  | 60 |  |
| 140 | Orc | Bowmen |  |  |  |  |  |  |
| 141 | Orc | Cavalry |  |  |  |  |  |  |
| 142 | Orc | Shaman |  |  |  |  |  |  |
| 143 | Orc | Magicians |  |  |  |  |  |  |
| 144 | Orc | Engineers |  |  |  |  |  |  |
| 145 | Orc | Settlers |  |  |  |  |  |  |
| 146 | Orc | Wyvern Riders | 8 |  |  |  | 250 | insufficiently strong for this tier |
| 147 | Troll | Spearmen |  |  |  |  |  |  |
| 148 | Troll | Swordsmen |  |  |  |  |  |  |
| 149 | Troll | Halberdiers | 8 |  |  |  | 200 |  |
| 150 | Troll | Shaman |  |  |  |  |  |  |
| 151 | Troll | Settlers |  |  |  |  |  |  |
| 152 | Troll | War Trolls |  |  |  |  | 250 |  |
| 153 | Troll | War Mammoths | 12 |  |  |  | 350 | a little improvement for top tier unit |
| 154 | Arcane | Magic Spirit |  |  |  |  |  |  |
| 155 | Chaos | Hell Hounds |  |  |  |  |  |  |
| 156 | Chaos | Gargoyles |  |  |  |  |  |  |
| 157 | Chaos | Fire Giant |  |  |  |  |  |  |
| 158 | Chaos | Fire Elemental |  |  |  |  |  |  |
| 159 | Chaos | Chaos Spawn |  |  |  |  |  |  |
| 160 | Chaos | Chimera |  |  |  | 6 |  |  |
| 161 | Chaos | Doom Bat | 15 |  |  | 30 |  | weak single figure unit |
| 162 | Chaos | Efreet | 15 | 15 |  | 15 |  |  |
| 163 | Chaos | Hydra |  |  |  | 5 | 1000 |  |
| 164 | Chaos | Great Drake |  |  |  |  | 2000 |  |
| 165 | Death | Skeletons |  |  |  |  |  |  |
| 166 | Death | Ghouls |  |  |  |  |  |  |
| 167 | Death | Night Stalker | 10 |  |  |  |  |  |
| 168 | Death | Werewolves |  |  |  |  |  |  |
| 169 | Death | Demon |  |  |  |  |  |  |
| 170 | Death | Wraiths |  |  |  |  |  |  |
| 171 | Death | Shadow Demons |  |  |  |  |  |  |
| 172 | Death | Death Knights |  |  |  |  | 1000 |  |
| 173 | Death | Demon Lord |  |  |  |  | 1500 |  |
| 174 | Death | Zombies |  |  |  |  |  |  |
| 175 | Life | Unicorns |  |  |  |  |  |  |
| 176 | Life | Guardian Spirit |  |  |  |  |  |  |
| 177 | Life | Angel |  |  |  |  |  |  |
| 178 | Life | Arch Angel |  |  |  |  |  |  |
| 179 | Nature | War Bears |  |  |  |  | 50 |  |
| 180 | Nature | Sprites |  |  |  |  |  |  |
| 181 | Nature | Cockatrices |  |  |  |  |  |  |
| 182 | Nature | Basilisk |  |  |  |  |  |  |
| 183 | Nature | Giant Spiders |  |  |  |  |  |  |
| 184 | Nature | Stone Giant |  |  |  |  |  |  |
| 185 | Nature | Colossus |  |  |  |  | 1400 |  |
| 186 | Nature | Gorgons |  |  |  |  | 800 |  |
| 187 | Nature | Earth Elemental |  |  |  |  |  |  |
| 188 | Nature | Behemoth |  |  |  |  | 1500 |  |
| 189 | Nature | Great Wyrm |  |  |  |  | 2000 |  |
| 190 | Sorcery | Floating Island |  |  |  |  |  |  |
| 191 | Sorcery | Phantom Beast |  |  |  |  |  |  |
| 192 | Sorcery | Phantom Warriors |  |  |  |  |  |  |
| 193 | Sorcery | Storm Giant |  |  |  |  |  |  |
| 194 | Sorcery | Air Elemental |  |  |  |  |  |  |
| 195 | Sorcery | Djinn |  |  |  |  |  |  |
| 196 | Sorcery | Sky Drake |  |  |  |  | 2500 |  |
| 197 | Sorcery | Nagas |  |  |  |  |  |  |

# Spells

_not implemented_

## General rules

1. More porwerful spell should be less mana efficient comparing to weaker version.
2. Positive unit enchantment upkeep is **doubled** to prevent player accumulating tons of buffs.
4. Overland enchantment annoying other wizards (Time Stop, Suppress Magic, Planar Seal, Armageddon, Great Wasting, etc.) upkeep is **quintupled**.
5. Universal non resistable damage spells (Doom Bolt, Disintegrate, etc.) casting cost is seriously increased.
6. Strong ability given unit enchantments (Flight, Invisibility, Magic Immunity, etc.) casting cost is seriosly increasd.

## Counter Magic

Power decreases by **25**, but only after successful countering.

## Summary table

| #| spell | cost | upkeep | comment |
| ----: | ---- | ----: | ----: | ---- |
| 1 | Earth to Mud | 5 |  | not too usable spell should be cheap |
| 2 | Resist Elements | 10 | 2 |  |
| 3 | Wall of Stone |  |  |  |
| 4 | Giant Strength |  |  |  |
| 5 | Web |  |  |  |
| 6 | War Bears |  |  |  |
| 7 | Stone Skin |  |  |  |
| 8 | Water Walking |  |  |  |
| 9 | Sprites |  |  |  |
| 10 | Earth Lore |  |  |  |
| 11 | Cracks Call | 60 |  | 25% killing chance should be expensive |
| 12 | Nature's Eye |  |  |  |
| 13 | Ice Bolt |  |  |  |
| 14 | Giant Spiders |  |  |  |
| 15 | Change Terrain |  |  |  |
| 16 | Path Finding |  |  |  |
| 17 | Cockatrices |  |  |  |
| 18 | Transmute |  |  |  |
| 19 | Nature's Cures |  |  |  |
| 20 | Basilisk |  |  |  |
| 21 | Elemental Armor | 50 | 10 |  |
| 22 | Petrify |  |  |  |
| 23 | Stone Giant |  |  |  |
| 24 | Iron Skin | 75 | 15 |  |
| 25 | Ice Storm |  |  |  |
| 26 | Earthquake |  |  |  |
| 27 | Gorgons |  |  |  |
| 28 | Move Fortress |  |  |  |
| 29 | Gaia's Blessing |  |  |  |
| 30 | Earth Elemental |  |  |  |
| 31 | Regeneration |  |  |  |
| 32 | Behemoth |  |  |  |
| 33 | Entangle | 25 |  | another rarely used spell |
| 34 | Nature Awareness |  |  |  |
| 35 | Call Lightning | 120 |  |  |
| 36 | Colossus |  |  |  |
| 37 | Earth Gate |  |  |  |
| 38 | Herb Mastery |  |  |  |
| 39 | Great Wyrm |  |  |  |
| 40 | Nature's Wrath |  | 50 |  |
| 41 | Resist Magic |  |  |  |
| 42 | Dispel Magic True |  |  |  |
| 43 | Floating Island |  |  |  |
| 44 | Guardian Wind | 20 | 4 | missile immunity should not be cheap |
| 45 | Phantom Warriors |  |  |  |
| 46 | Confusion | 30 |  | notoriously OP |
| 47 | Word of Recall |  |  |  |
| 48 | Counter Magic |  |  |  |
| 49 | Nagas |  |  |  |
| 50 | Psionic Blast |  |  |  |
| 51 | Blur |  |  |  |
| 52 | Disenchant True |  |  |  |
| 53 | Vertigo |  |  |  |
| 54 | Spell Lock |  | 2 |  |
| 55 | Enchant Road |  |  |  |
| 56 | Flight | 50 | 10 |  |
| 57 | Wind Mastery |  |  |  |
| 58 | Spell Blast |  |  |  |
| 59 | Aura of Majesty |  |  |  |
| 60 | Phantom Beast |  |  |  |
| 61 | Disjunction True |  |  |  |
| 62 | Invisiblity | 70 | 15 |  |
| 63 | Wind Walking | 500 | 25 |  |
| 64 | Banish |  |  |  |
| 65 | Storm Giant |  |  |  |
| 66 | Air Elemental |  |  |  |
| 67 | Mind Storm | 125 |  | non resistable -5 everything |
| 68 | Stasis |  |  |  |
| 69 | Magic Immunity | 100 | 20 |  |
| 70 | Haste |  |  |  |
| 71 | Djinn |  |  |  |
| 72 | Spell Ward |  |  |  |
| 73 | Creature Binding |  |  |  |
| 74 | Mass Invisibility | 150 |  |  |
| 75 | Great Unsummoning |  |  |  |
| 76 | Spell Binding |  |  |  |
| 77 | Flying Fortress |  |  |  |
| 78 | Sky Drake |  |  |  |
| 79 | Suppress Magic |  | 250 |  |
| 80 | Time Stop |  | 1000 |  |
| 81 | Warp Wood | 20 |  | guardian wind on opponent |
| 82 | Disrupt |  |  |  |
| 83 | Fire Bolt |  |  |  |
| 84 | Hell Hounds |  |  |  |
| 85 | Corruption | 100 |  | just for AI not to use it too often |
| 86 | Eldritch Weapon |  | 3 |  |
| 87 | Wall of Fire |  |  |  |
| 88 | Shatter |  |  |  |
| 89 | Warp Creature |  |  |  |
| 90 | Fire Elemental |  |  |  |
| 91 | Lightning Bolt |  |  |  |
| 92 | Fire Giant |  |  |  |
| 93 | Chaos Channels |  |  |  |
| 94 | Flame Blade |  | 4 |  |
| 95 | Gargoyles |  |  |  |
| 96 | Fireball |  |  |  |
| 97 | Doom Bat |  |  |  |
| 98 | Raise Volcano |  |  |  |
| 99 | Immolation |  |  |  |
| 100 | Chimeras |  |  |  |
| 101 | Warp Lightning |  |  |  |
| 102 | Metal Fires | 60 |  |  |
| 103 | Chaos Spawn |  |  |  |
| 104 | Doom Bolt | 100 |  | another universal guaranteed damage |
| 105 | Magic Vortex |  |  |  |
| 106 | Efreet |  |  |  |
| 107 | Fire Storm |  |  |  |
| 108 | Warp Reality |  |  |  |
| 109 | Flame Strike | 125 |  | equivalent of nine 15 strength fireballs |
| 110 | Chaos Rift |  |  |  |
| 111 | Hydra |  |  |  |
| 112 | Disintegrate | 100 |  |  |
| 113 | Meteor Storm |  |  |  |
| 114 | Great Wasting |  | 100 |  |
| 115 | Call Chaos |  |  |  |
| 116 | Chaos Surge |  |  |  |
| 117 | Doom Mastery |  |  |  |
| 118 | Great Drake |  |  |  |
| 119 | Call the Void |  |  |  |
| 120 | Armageddon |  | 200 |  |
| 121 | Bless |  |  |  |
| 122 | Star Fires |  |  |  |
| 123 | Endurance |  |  |  |
| 124 | Holy Weapon | 25 | 5 |  |
| 125 | Healing |  |  |  |
| 126 | Holy Armor | 30 | 6 |  |
| 127 | Just Cause |  |  |  |
| 128 | True Light | 30 |  |  |
| 129 | Guardian Spirit |  |  |  |
| 130 | Heroism | 40 | 8 |  |
| 131 | True Sight |  |  |  |
| 132 | Plane Shift |  |  |  |
| 133 | Resurrection |  |  |  |
| 134 | Dispel Evil |  |  |  |
| 135 | Planar Seal |  | 25 |  |
| 136 | Unicorns |  |  |  |
| 137 | Raise Dead |  |  |  |
| 138 | Planar Travel |  |  |  |
| 139 | Heavenly Light |  |  |  |
| 140 | Prayer | 60 |  |  |
| 141 | Lionheart | 75 | 15 |  |
| 142 | Incarnation | 1000 |  | should not be cheaper than champion |
| 143 | Invulnerability | 60 | 15 |  |
| 144 | Righteousness | 60 | 12 |  |
| 145 | Prosperity |  |  |  |
| 146 | Altar of Battle |  |  |  |
| 147 | Angel |  |  |  |
| 148 | Stream of Life |  |  |  |
| 149 | Mass Healing |  |  |  |
| 150 | Holy Word |  |  |  |
| 151 | High Prayer | 150 |  |  |
| 152 | Inspirations |  |  |  |
| 153 | Astral Gate |  |  |  |
| 154 | Holy Arms |  |  |  |
| 155 | Consecration |  |  |  |
| 156 | Life Force |  | 50 |  |
| 157 | Tranquility |  | 50 |  |
| 158 | Crusade |  |  |  |
| 159 | Arch Angel |  |  |  |
| 160 | Charm of Life |  |  |  |
| 161 | Skeletons |  |  |  |
| 162 | Weakness |  |  |  |
| 163 | Dark Rituals |  |  |  |
| 164 | Cloak of Fear |  |  |  |
| 165 | Black Sleep | 30 |  |  |
| 166 | Ghouls |  |  |  |
| 167 | Life Drain |  |  |  |
| 168 | Terror |  |  |  |
| 169 | Darkness | 30 |  |  |
| 170 | Mana Leak | 40 |  |  |
| 171 | Drain Power |  |  |  |
| 172 | Possession |  |  |  |
| 173 | Lycanthropy |  |  |  |
| 174 | Black Prayer | 50 |  |  |
| 175 | Black Channels |  |  |  |
| 176 | Night Stalker |  |  |  |
| 177 | Subversion |  |  |  |
| 178 | Wall of Darkness |  |  |  |
| 179 | Berserk | 45 |  |  |
| 180 | Shadow Demons |  |  |  |
| 181 | Wraith Form |  |  |  |
| 182 | Wrack | 60 |  |  |
| 183 | Evil Presence |  |  |  |
| 184 | Wraiths |  |  |  |
| 185 | Cloud of Shadow |  |  |  |
| 186 | Warp Node |  |  |  |
| 187 | Black Wind |  |  |  |
| 188 | Zombie Mastery |  |  |  |
| 189 | Famine |  |  |  |
| 190 | Cursed Lands |  |  |  |
| 191 | Cruel Unminding |  |  |  |
| 192 | Word of Death |  |  |  |
| 193 | Death Knights |  |  |  |
| 194 | Death Spell |  |  |  |
| 195 | Animate Dead |  |  |  |
| 196 | Pestilence |  |  |  |
| 197 | Eternal Night |  |  |  |
| 198 | Evil Omens |  | 50 |  |
| 199 | Death Wish |  |  |  |
| 200 | Demon Lord |  |  |  |
| 201 | Magic Spirit |  |  |  |
| 202 | Dispel Magic |  |  |  |
| 203 | Summoning Circle |  |  |  |
| 204 | Disenchant Area |  |  |  |
| 205 | Recall Hero |  |  |  |
| 206 | Detect Magic |  |  |  |
| 207 | Enchant Item |  |  |  |
| 208 | Summon Hero |  |  |  |
| 209 | Awareness |  |  |  |
| 210 | Disjunction |  |  |  |
| 211 | Create Artifact |  |  |  |
| 212 | Summon Champion |  |  |  |
| 213 | Spell of Mastery | 10000 |  | should take longer for other wizards to fight the caster |
| 214 | Spell of Return | 500 |  | should not take too long |

# Patches

| filename | effect |
| ---- | ---- |
| WFDGD20.TXT | Excess food to gold conversion ratio = 1:2 |
| WFDUPK05.TXT  | Units food support = 1/2 |
| WUNITS.TXT | Cumulative unit changes |
| WHEROES.TXT | Hero changes |
| WCOUNTER.TXT  | Counter Magic adjustmetns |

