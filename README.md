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
3. Experienced heroes are _slightly_ more tough and better. They will die less frequent and player should not pay extra attention on protecting them.
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
| 160 | Chaos | Chimera | 6 |  | 3 |  |  |  |
| 161 | Chaos | Doom Bat | 15 |  |  |  |  |  |
| 162 | Chaos | Efreet | 15 |  |  |  |  |  |
| 163 | Chaos | Hydra |  |  |  | 5 |  |  |
| 164 | Chaos | Great Drake |  |  |  |  | 1500 |  |
| 165 | Death | Skeletons |  |  |  |  |  |  |
| 166 | Death | Ghouls |  |  |  |  |  |  |
| 167 | Death | Night Stalker | 10 |  |  |  |  |  |
| 168 | Death | Werewolves |  |  |  |  |  |  |
| 169 | Death | Demon |  |  |  |  |  |  |
| 170 | Death | Wraiths |  |  |  |  |  |  |
| 171 | Death | Shadow Demons |  |  |  |  |  |  |
| 172 | Death | Death Knights |  |  |  |  |  |  |
| 173 | Death | Demon Lord |  |  |  |  |  |  |
| 174 | Death | Zombies |  |  |  |  |  |  |
| 175 | Life | Unicorns |  |  |  |  |  |  |
| 176 | Life | Guardian Spirit |  |  |  |  |  |  |
| 177 | Life | Angel |  |  |  |  |  |  |
| 178 | Life | Arch Angel |  |  |  |  |  |  |
| 179 | Nature | War Bears |  |  |  |  |  |  |
| 180 | Nature | Sprites |  |  |  |  |  |  |
| 181 | Nature | Cockatrices |  |  |  |  |  |  |
| 182 | Nature | Basilisk |  |  |  |  |  |  |
| 183 | Nature | Giant Spiders |  |  |  |  |  |  |
| 184 | Nature | Stone Giant |  |  |  |  |  |  |
| 185 | Nature | Colossus |  |  |  |  |  |  |
| 186 | Nature | Gorgons |  |  |  |  |  |  |
| 187 | Nature | Earth Elemental |  |  |  |  |  |  |
| 188 | Nature | Behemoth |  |  |  |  |  |  |
| 189 | Nature | Great Wyrm |  |  |  |  |  |  |
| 190 | Sorcery | Floating Island |  |  |  |  |  |  |
| 191 | Sorcery | Phantom Beast |  |  |  |  |  |  |
| 192 | Sorcery | Phantom Warriors |  |  |  |  |  |  |
| 193 | Sorcery | Storm Giant |  |  |  |  |  |  |
| 194 | Sorcery | Air Elemental |  |  |  |  |  |  |
| 195 | Sorcery | Djinn |  |  |  |  |  |  |
| 196 | Sorcery | Sky Drake |  |  |  |  |  |  |
| 197 | Sorcery | Nagas |  |  |  |  |  |  |

# Spells

## General rules

1. More porwerful spell should be unproportionally more expensive to present speed vs. mana efficiency choice to the player.
2. Long lasting effect spells (protective) should cost proportionally more than one time effect ones (damage).
3. All anti-magic overland enchantments should have super high upkeep. Wizard should pay a every turn premium suppressing other players.
4. All super nasty overland enchantments (Armageddon, Great Wasting) should have super high upkeep.

## Counter Magic

Power decreases by **25**, but only after successful countering.

## Summary table

_not implemented_

| spell | overland | combat | upkeep | comment |
| ---- | ----: | ----: | ----: | ---- |
| Heroism | 200 | 40 | 8 |  |
| High Prayer |  | 150 |  |  |
| Holy Armor | 100 | 20 | 4 |  |
| Holy Weapon | 50 | 10 | 2 |  |
| Incarnation | 1000 |  |  | should be more expensive than summoning a champion |
| Invulnerability | 300 | 60 | 12 |  |
| Life Force |  |  | 50 |  |
| Lionheart | 400 | 80 | 16 |  |
| Planar Seal |  |  | 25 |  |
| Prayer |  | 60 |  |  |
| Righteousness | 300 | 60 | 6 |  |
| Tranquility |  |  | 50 |  |
| True Light |  |  | 30 |  |
| Call Lightning |  | 100 |  |  |
| Cracks Call |  | 100 |  | 25% killing chance for 20 mana ?? |
| Earth to Mud |  | 5 |  | this was too overpriced for the effect |
| Entangle |  | 25 |  | another rarely used spell due to its price |
| Iron Skin | 300 | 60 | 12 |  |
| Nature's Wrath |  |  | 50 |  |
| Confusion |  | 30 |  |  |
| Enchant Road | 200 |  |  |  |
| Flight | 250 | 50 | 10 |  |
| Invisibility | 350 | 70 | 20 |  |
| Magic Immunity | 500 | 100 | 20 |  |
| Mass Invisibility |  | 160 |  |  |
| Mind Storm |  | 100 |  | unresistable -5 everything |
| Suppress Magic |  |  | 250 |  |
| Time Stop |  |  | 1000 |  |
| Armageddon |  |  | 200 |  |
| Chaos Channels | 200 |  |  |  |
| Corruption | 100 |  |  | to prevent AI wizards from casting it all the time |
| Doom Bolt |  | 100 |  | ignore everything super damage |
| Eldritch Weapon | 100 | 20 | 4 |  |
| Flame Blade | 125 | 25 | 4 |  |
| Great Wasting |  |  | 100 |  |
| Metal Fires |  | 60 |  |  |
| Meteor Storm |  |  | 50 |  |
| Warp Wood |  | 20 |  |  |
| Black Prayer |  | 60 |  |  |
| Black Sleep |  | 30 |  |  |
| Death Wish | 1000 |  |  | too cheap for killing 50% of units worldwide |
| Evil Omens |  |  | 50 |  |
| Mana Leak |  | 40 |  |  |
| Wrack |  | 60 |  |  |
| Zombie Mastery |  |  | 80 |  |
| Spell of Mastery | 10000 |  |  | it was too close to other spell costs |
| Spell of Return | 500 |  |  | reducing losing the castle city consequence |

# Patches

| filename | effect |
| ---- | ---- |
| WFDGD20.TXT | Excess food to gold conversion ratio = 1:2 |
| WFDUPK05.TXT  | Units food support = 1/2 |
| WUNITS.TXT | Cumulative unit changes |
| WHEROES.TXT | Hero changes |
| WCOUNTER.TXT  | Counter Magic adjustmetns |

