# Master of magic strategy balancing mod

Attempt to modify different aspects of the game to make them more usable and give existing underdog strategies second life.

# Installation

Prerequisite: Master of Magic Community Patch (from GOG or Slitherine).

1. Download files from `patches/cumulative` folder.
2. Run DOSBox and switch to game folder.
3. Run following commands.

```
FILESET.EXE WIZARDS.EXE <path to downloaded WIZARDS.TXT>
FILESET.EXE SPELLDAT.LBX <path to downloaded SPELLDAT.TXT>
```

# Idea

MoM is exceptionally feature reach game. Unfortunately, due to some balance skews, a lot of interesting strategies are unfeasible/ineffective and, therefore, never used. The goal of this mod is to modify balance in a way to give them a second life and restore this game glory as true strategy reach one as it should be.

Some example user complaints can be found here: https://www.realmsbeyond.net/forums/showthread.php?tid=4966

# Problems addressing

## Units

### Normal unit army strategy is unfeasible

* Food upkeep is too restrictive prohibiting to have barely decent size army and operate at all directions.
* Basic unit types seem to be jammed into lower strength niche and redundant.
  * Spearmen are mostly police throughtout the game. Occasionally as a supplemental force against low level neutrals early game.
  * Swordsmen can be built in small quantity in first town to supplement low level neutral attack early game. Never since.
  * Cavalry is never built.
  * Halberdiers are too weak comparing to their infrastructure investment.
  * Bowmen are excellent against early game phantom warriors/beasts. Never after.
  * Shamans are for purifying only. Never for combat.
* XP advancement is skewed. It is very easy to accumulate it just doing nothing, but reward is measly for first two levels. No insentive to fight for XP or utilize Armsmaster.
* Combat XP is awarded equally to every participant. That forces player to stack their heroes/armies together for free XP even if they are strong enough fighting on their own.

### General imbalance in unit strengths

Some units (heroes, normal, summoned) are just plain weaker than other and are never built/summoned.

## Magic

### Magic favors protection rather than damage

Many people notice that protective magic is more effective than damaging one. Indeed, damaging opponent is an one time effect. Whereas protection acts every time unit is targeted, benefiting over and over again. Most protective spells have also relatively low upkeep allowing unit (usually hero) to be overenchanted and turned into killing machine _without spending extra_ in combat! That is a defniite imbalance.

### General imbalance in spell effect vs. casting cost and upkeep

Same story as always. Some spells are better than others.

### Counter Magic OP

Casting 50 strength Counter Magic erects **10 turns** force field disrupting enemy wizards casting (including counter Counter Magic) and, at the same time, allowing its owner to cast whaterver they want. That is an immense adavantage understandable even to AI.

### Spell save imbalance

* Some spells have much better save (= better success chance) that others despite their effect. It can be allowed for more rare and more expensive spells, but not for common cheap ones.
* Item spell save can amount to -12, which is huge bonus. This does not seem like a big problem, though, due to the bonus rarity and high crafting cost.

# Fix: Normal units food upkeep

* Normal unit food upkeep is set to 1/2.
* Optionally, food upkeep can be eliminated alltogether. However, the above change seems to be sufficient. Please share feedback.

Player can have larger army without exhausting their food supply. This seems to run extremely satisfactory. Army size is not hard limited by food harvesting anymore. It keeps consuming gold but this is more flexible due to centralized distribution and stockpiled reserves. Occasional worker reallocation is still needed but not that often.

# Fix: Unit balance

## Normal units

### General rules

* More advanced unit that requires more buildings should be adequately stronger and proportionally more expensive.
* Some top tier racial units are adjusted to stay competitive among other races top tier units.

### Standard unit stats

_modification is in progress_

* Standard melee units are spreaded out a little to fill up the niche between Spearmen and Pikemen more evenly.

| type | melee | range | defense | cost | comment |
| ---- | ---: | ---: | ---: | ---: | ---- |
| Spearmen |  |  |  |  |  |
| Swordsmen |  |  |  |  |  |
| Cavalry | +1 |  |  | x1.5 | slight improvement for fast strike unit |
| Halberdiers | +2 |  | +2 | x2.0 | making them more distinct from Cavalry and closer to Pikemen |
| Pikemen |  |  |  |  |  |
| Bowmen |  |  |  |  |  |
| Shaman |  | +1 |  |  | feel weak and unused |
| Magicians |  | +1 |  |  | pathetic damage for the most expensive infrastructure |
| Priests |  |  |  |  |  |
| H.Men Magicians |  |  |  |  |  |

### Warship

* Limited shots to 10.

### Magicians

* High Men Magicians are more expensive due to their increased figure count.
* Other races Magicians (except Warlocks) have +1 to their ranged attack. Otherwise, they do not seem worth infrastructure investment.

## Heroes

### Hero survivability

* All heroes (except few OP ones) receive +5 HP.
* Some badly advanceable heroes recevie significant stat boost to make them worth their price at least initially.

Increasing heroes HP makes them much less fragile, especially at the beginning. They can engage with low level units earning their XP in honest fight instead of sitting on the bench during combat. They require much less babysitting and protecting. They still incur damage but do not die in a single blow exchange and can be pulled out of the battle in time when their HP drops too low. Overall it feels like they play their role now leading a battle and augmenting player's forces rather than being some non-combat toy.

Extra HP does not make them OP at higher XP levels either as their armor is still penetrable. They just live little longer. Because of this player does not need to retain them at all costs. They may still die occasionally, but much less often and the replacement is not that bad either.

## Fantastic units

* Units stats (strength, cost) are adjusted to make them adequately placed on research timeline.

## Summary table

<details>

<summary>Unit stats</summary>

| # | race | name | me | ra | de | HP | cost | comment |
| ----: | ---- | ---- | ----: | ----: | ----: | ----: | ----: | ---- |
| 0 | Dwarven | Dwarf | 7 |  | 5 | 15 |  | not too advanceable |
| 1 | Barbarian | Barbarian |  |  |  | 14 |  |  |
| 2 | High Men | Sage |  |  |  | 10 |  |  |
| 3 | High Men | Dervish |  |  |  | 11 |  |  |
| 4 | Beastmen | Beastmaster | 9 |  | 6 | 12 |  | the most unadvanceable hero |
| 5 | High Men | Bard | 7 |  | 7 | 11 |  | not too strong even with Leadership |
| 6 | Orc | Orc Warrior |  |  |  | 13 |  |  |
| 7 | High Men | Healer |  |  |  | 10 |  |  |
| 8 | High Men | Huntress |  |  |  | 12 |  |  |
| 9 | High Men | Thief |  |  |  | 12 |  |  |
| 10 | High Men | Driud |  |  |  | 10 |  |  |
| 11 | High Men | War Monk |  |  |  | 11 |  |  |
| 12 | High Men | Warrior Mage | 7 | 7 |  | 12 |  | short mana supply and measly stats |
| 13 | High Men | Magician |  | 4 |  | 10 |  | super OP guy - still very strong even with this handicap |
| 14 | High Men | Assassin | 8 |  |  | 11 |  | lack of swords to utilize Blademaster |
| 15 | High Men | Wind Mage |  |  |  | 10 |  |  |
| 16 | High Men | Ranger |  |  |  | 13 |  |  |
| 17 | Draconian | Draconian |  |  |  | 13 |  |  |
| 18 | High Men | Witch |  |  |  | 10 |  |  |
| 19 | High Men | Golden One |  |  |  | 11 |  |  |
| 20 | High Men | Ninja | 7 |  |  | 12 |  | lack of swords to utilize Blademaster |
| 21 | High Men | Rogue | 11 |  | 7 | 13 |  | uninteresting guy - giving him a lot of initial boost |
| 22 | High Men | Amazon |  |  |  | 13 |  |  |
| 23 | High Men | Warlock |  |  |  | 10 |  |  |
| 24 | High Men | Unknown |  |  |  | 13 |  |  |
| 25 | High Men | Illusionist |  |  |  | 10 |  | lack of attack to utilize Illusion |
| 26 | High Men | Swordsman | 12 |  |  | 15 |  | flat guy - giving swordsman more themed swords |
| 27 | High Men | Priestess |  |  |  | 10 |  |  |
| 28 | High Men | Paladin |  |  |  | 13 |  |  |
| 29 | High Men | Black Knight |  |  |  |  |  | the most powerful guy even without HP boost |
| 30 | High Elf | Elven Archer |  |  |  | 11 |  | let her be archer |
| 31 | High Men | Knight |  |  | 9 | 14 |  | flat guy - giving knight in shiny armor more themed armor |
| 32 | High Men | Necromancer |  |  |  | 10 |  |  |
| 33 | High Men | Chaos Warrior |  | 4 |  | 13 |  | super OP with Arcane Power |
| 34 | Life | Chosen |  |  |  |  |  |  |
| 35 | Generic | Trireme |  |  |  |  |  |  |
| 36 | Generic | Galley |  |  |  |  |  |  |
| 37 | Generic | Catapult |  |  |  |  |  |  |
| 38 | Generic | Warship |  |  |  |  | 500 |  |
| 39 | Barbarian | Spearmen |  |  |  |  |  |  |
| 40 | Barbarian | Swordsmen |  |  |  |  |  |  |
| 41 | Barbarian | Bowmen |  |  |  |  |  |  |
| 42 | Barbarian | Cavalry | 5 |  |  |  | 100 |  |
| 43 | Barbarian | Shaman |  | 3 |  |  |  |  |
| 44 | Barbarian | Settlers |  |  |  |  |  |  |
| 45 | Barbarian | Berserkers | 9 | 4 |  |  | 150 | slightly weak for hight end unit |
| 46 | Beastmen | Spearmen |  |  |  |  |  |  |
| 47 | Beastmen | Swordsmen |  |  |  |  |  |  |
| 48 | Beastmen | Halberdiers | 7 |  | 5 |  | 150 |  |
| 49 | Beastmen | Bowmen |  |  |  |  |  |  |
| 50 | Beastmen | Priests |  |  |  |  |  |  |
| 51 | Beastmen | Magicians |  | 6 |  |  |  |  |
| 52 | Beastmen | Engineers |  |  |  |  |  |  |
| 53 | Beastmen | Settlers |  |  |  |  |  |  |
| 54 | Beastmen | Centaurs | 4 |  |  |  |  | some boost to match the improved Cavalry |
| 55 | Beastmen | Manticores | 10 |  | 6 |  |  | too weak for higher tier creature |
| 56 | Beastmen | Minotaurs |  |  |  |  | 250 |  |
| 57 | Dark Elf | Spearmen |  |  |  |  | 40 |  |
| 58 | Dark Elf | Swordsmen |  |  |  |  |  |  |
| 59 | Dark Elf | Halberdiers | 6 |  | 5 |  | 150 |  |
| 60 | Dark Elf | Cavalry | 5 |  |  |  |  |  |
| 61 | Dark Elf | Priests |  |  |  |  |  |  |
| 62 | Dark Elf | Settlers |  |  |  |  |  |  |
| 63 | Dark Elf | Nightblades | 6 |  | 5 |  | 200 | matching halberdiers |
| 64 | Dark Elf | Warlocks |  |  |  |  | 400 |  |
| 65 | Dark Elf | Nightmares |  | 8 |  |  | 300 | too weak for top end magical race flying shooter |
| 66 | Draconian | Spearmen |  |  |  |  |  |  |
| 67 | Draconian | Swordsmen |  |  |  |  |  |  |
| 68 | Draconian | Halberdiers | 6 |  | 6 |  | 150 |  |
| 69 | Draconian | Bowmen |  |  |  |  |  |  |
| 70 | Draconian | Shaman |  | 3 |  |  |  |  |
| 71 | Draconian | Magicians |  | 6 |  |  |  |  |
| 72 | Draconian | Engineers |  |  |  |  |  |  |
| 73 | Draconian | Settlers |  |  |  |  |  |  |
| 74 | Draconian | Doom Drakes |  |  |  |  | 200 |  |
| 75 | Draconian | Air Ship |  |  |  |  | 300 |  |
| 76 | Dwarven | Swordsmen |  |  |  |  |  |  |
| 77 | Dwarven | Halberdiers | 6 |  | 5 |  | 200 |  |
| 78 | Dwarven | Engineers |  |  |  |  |  |  |
| 79 | Dwarven | Hammerhands |  |  |  |  | 250 |  |
| 80 | Dwarven | Steam Cannon |  |  |  |  |  |  |
| 81 | Dwarven | Golem | 16 |  |  |  | 250 | should be stronger than hammerhands |
| 82 | Dwarven | Settlers |  |  |  |  |  |  |
| 83 | Gnoll | Spearmen |  |  |  |  |  |  |
| 84 | Gnoll | Swordsmen |  |  |  |  |  |  |
| 85 | Gnoll | Halberdiers | 8 |  | 5 |  | 80 |  |
| 86 | Gnoll | Bowmen |  |  |  |  |  |  |
| 87 | Gnoll | Settlers |  |  |  |  |  |  |
| 88 | Gnoll | Wolf Riders |  |  |  |  |  |  |
| 89 | Halfling | Spearmen |  |  |  |  |  |  |
| 90 | Halfling | Swordsmen |  |  |  |  |  |  |
| 91 | Halfling | Bowmen |  |  |  |  |  |  |
| 92 | Halfling | Shaman |  | 3 |  |  |  |  |
| 93 | Halfling | Settlers |  |  |  |  |  |  |
| 94 | Halfling | Slingers |  |  |  |  |  |  |
| 95 | High Elf | Spearmen |  |  |  |  |  |  |
| 96 | High Elf | Swordsmen |  |  |  |  |  |  |
| 97 | High Elf | Halberdiers | 6 |  | 5 |  | 120 |  |
| 98 | High Elf | Cavalry | 5 |  |  |  | 100 |  |
| 99 | High Elf | Magicians |  | 6 |  |  |  |  |
| 100 | High Elf | Settlers |  |  |  |  |  |  |
| 101 | High Elf | Longbowmen |  |  |  |  | 120 |  |
| 102 | High Elf | Elven Lords |  |  |  |  |  |  |
| 103 | High Elf | Pegasai |  | 5 |  |  | 200 | some boost for high end unit |
| 104 | High Men | Spearmen |  |  |  |  |  |  |
| 105 | High Men | Swordsmen |  |  |  |  |  |  |
| 106 | High Men | Bowmen |  |  |  |  |  |  |
| 107 | High Men | Cavalry | 5 |  |  |  | 60 |  |
| 108 | High Men | Priests |  |  |  |  |  |  |
| 109 | High Men | Magicians |  |  |  |  |  |  |
| 110 | High Men | Engineers |  |  |  |  |  |  |
| 111 | High Men | Settlers |  |  |  |  |  |  |
| 112 | High Men | Pikemen |  |  |  |  | 120 |  |
| 113 | High Men | Paladins |  |  |  |  | 300 |  |
| 114 | Klackon | Spearmen |  |  |  |  |  |  |
| 115 | Klackon | Swordsmen |  |  |  |  |  |  |
| 116 | Klackon | Halberdiers | 6 |  | 7 |  | 150 |  |
| 117 | Klackon | Engineers |  |  |  |  |  |  |
| 118 | Klackon | Settlers |  |  |  |  |  |  |
| 119 | Klackon | Stag Beetle |  |  |  |  | 300 |  |
| 120 | Lizardman | Spearmen |  |  |  |  |  |  |
| 121 | Lizardman | Swordsmen |  |  |  |  |  |  |
| 122 | Lizardman | Halberdiers | 6 |  | 6 |  | 100 |  |
| 123 | Lizardman | Javelineers |  |  |  |  | 100 |  |
| 124 | Lizardman | Shaman |  | 3 | 4 |  |  |  |
| 125 | Lizardman | Settlers |  |  |  |  |  |  |
| 126 | Lizardman | Dragon Turtle | 15 |  |  |  | 250 | should be worth the investments |
| 127 | Nomad | Spearmen |  |  |  |  |  |  |
| 128 | Nomad | Swordsmen |  |  |  |  |  |  |
| 129 | Nomad | Bowmen |  |  |  |  |  |  |
| 130 | Nomad | Priests |  |  |  |  |  |  |
| 131 | Nomad | Magicians |  | 6 |  |  |  |  |
| 132 | Nomad | Settlers |  |  |  |  |  |  |
| 133 | Nomad | Horsebowmen | 5 |  |  |  | 100 | matching cavalry |
| 134 | Nomad | Pikemen |  |  |  |  | 120 |  |
| 135 | Nomad | Rangers |  | 5 |  |  | 150 | little buff to high end unit |
| 136 | Nomad | Griffins |  |  |  |  | 250 |  |
| 137 | Orc | Spearmen |  |  |  |  |  |  |
| 138 | Orc | Swordsmen |  |  |  |  |  |  |
| 139 | Orc | Halberdiers | 6 |  | 5 |  | 80 |  |
| 140 | Orc | Bowmen |  |  |  |  |  |  |
| 141 | Orc | Cavalry | 5 |  |  |  | 60 |  |
| 142 | Orc | Shaman |  | 3 |  |  |  |  |
| 143 | Orc | Magicians |  | 6 |  |  |  |  |
| 144 | Orc | Engineers |  |  |  |  |  |  |
| 145 | Orc | Settlers |  |  |  |  |  |  |
| 146 | Orc | Wyvern Riders | 9 |  | 7 |  | 250 |  |
| 147 | Troll | Spearmen |  |  |  |  |  |  |
| 148 | Troll | Swordsmen |  |  |  |  |  |  |
| 149 | Troll | Halberdiers |  |  |  |  | 100 | too strong with same halberdiers buff |
| 150 | Troll | Shaman |  | 3 |  |  |  |  |
| 151 | Troll | Settlers |  |  |  |  |  |  |
| 152 | Troll | War Trolls |  |  |  |  | 200 |  |
| 153 | Troll | War Mammoths | 12 |  |  |  | 300 |  |
| 154 | Arcane | Magic Spirit |  |  |  |  |  |  |
| 155 | Chaos | Hell Hounds |  |  |  |  |  |  |
| 156 | Chaos | Gargoyles |  |  |  |  |  |  |
| 157 | Chaos | Fire Giant |  |  |  |  |  |  |
| 158 | Chaos | Fire Elemental |  |  |  |  |  |  |
| 159 | Chaos | Chaos Spawn |  |  |  |  |  |  |
| 160 | Chaos | Chimera |  |  | 3 |  |  |  |
| 161 | Chaos | Doom Bat | 14 |  |  |  |  |  |
| 162 | Chaos | Efreet | 15 | 15 | 10 |  |  | was too weak for its rarity |
| 163 | Chaos | Hydra |  |  |  |  |  |  |
| 164 | Chaos | Great Drake |  |  |  |  |  |  |
| 165 | Death | Skeletons |  |  |  |  |  |  |
| 166 | Death | Ghouls |  |  |  |  |  |  |
| 167 | Death | Night Stalker | 10 |  |  |  |  |  |
| 168 | Death | Werewolves |  |  |  |  |  |  |
| 169 | Death | Demon |  |  |  |  |  |  |
| 170 | Death | Wraiths |  |  |  |  |  |  |
| 171 | Death | Shadow Demons |  |  |  |  |  |  |
| 172 | Death | Death Knights |  |  | 6 |  |  |  |
| 173 | Death | Demon Lord |  |  |  |  |  |  |
| 174 | Death | Zombies |  |  |  |  |  |  |
| 175 | Life | Unicorns |  |  |  |  |  |  |
| 176 | Life | Guardian Spirit |  |  |  |  |  |  |
| 177 | Life | Angel |  |  |  |  |  |  |
| 178 | Life | Arch Angel |  |  |  |  |  |  |
| 179 | Nature | War Bears |  |  |  |  | 50 |  |
| 180 | Nature | Sprites |  |  |  |  |  |  |
| 181 | Nature | Cockatrices | 6 |  |  |  |  | a little bit weak even with stoning touch |
| 182 | Nature | Basilisk |  |  |  |  |  |  |
| 183 | Nature | Giant Spiders | 8 |  | 4 |  |  | too weak for their cost |
| 184 | Nature | Stone Giant |  |  |  |  |  |  |
| 185 | Nature | Colossus |  |  |  |  |  |  |
| 186 | Nature | Gorgons |  |  |  |  | 600 |  |
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

</details>

# Fix: Experience levels

* Normal units and heroes **do not** get +1 experience each turn.
* Combat experience is **divided** among survivors. Experimental: Please report any discrepancies on it.
* Normal unit experience level bonuses are slightly improved.

Experience is not cheap anymore. Doing nothing for 20 turns does not grant next level. Unit has to fight for it. XP buildings and Armsmaster heroes become more valuable as they are only non-combat source of experience.

At the same time, total combat experience is a fixed pool equally distributed among survivors (including summoned creatures). No need for combining heroes/armies for the sole purpose of reaping more XP. There is NO "more XP". Player can concentrate on strategical efficiency instead of XP grinding. Smaller number of more efficient troops get more XP than large quantity of weak and badly matched ones.

There is also a question of *how much* experience they should receive from each fallen enemy. Currently, it is original default: 2. However, with fixed experience pool, there may be need to increase it to match OG progression. Need to playtest and see. Please report your observations.

## Normal unit experience level bonuses summary table

Both Regular and Veteran get two nice synergetic improvements. Elite still has strong bonus of +1 HP, which doubles low level unit toughness. Champions get three super cool improvements as it was in OG and how it should be.

Changes are bolded. Level improvements are underscored.

| level | `attack    ` | `toHit     ` | `defense   ` | `resistance` | `hit points` |
| ---- | ----: | ----: | ----: | ----: | ----: |
| Recruit |  |  |  |  |  |
| Regular | <ins>+1</ins> |  | <ins>**+1**</ins> | <ins>+1</ins> |  |
| Veteran | <ins>**+2**</ins> | <ins>**+1**</ins> | +1 | <ins>+2</ins> |  |
| Elite | <ins>**+3**</ins> | +1 | +1 | <ins>+3</ins> | <ins>+1</ins> |
| Ultra-Elite | **+3** | <ins>+2</ins> | <ins>+2</ins> | <ins>+4</ins> | +1 |
| Champion | <ins>**+4**</ins> | <ins>+3</ins> | +2 | <ins>+5</ins> | <ins>+2</ins> |

# Fix: Spell balance

## General rules

* More porwerful spell should be less mana efficient comparing to weaker version.
  * More rare spells are allowed to be somewhat more effective as it takes time and efforts to acquire them and even that is not guaranteed.
* Positive unit enchantment upkeep is **doubled** to prevent accumulating tons of permanent buffs.
* Overland enchantment annoying other wizards (Time Stop, Suppress Magic, Planar Seal, Armageddon, Great Wasting, etc.) upkeep is **quintupled**.
* Universal non resistable damage spells (Doom Bolt, Disintegrate, etc.) casting cost is seriously increased.
* Strong ability given unit enchantments (Flight, Invisibility, Magic Immunity, etc.) casting cost is seriosly increasd.

## Counter Magic

* Power decreases by **25**, but only after successful countering. I am not sure this is working. Need to review the code.

That eliminates its abusive use to cast 50 strength magical shield and stay protected for 10 (**ten**) turns while continuing mollesting opponent with damaging spells. With above change it is down by 1-2 turns.

## Summary table

<details>

<summary>Spell stats</summary>

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
| 172 | Possession | 50 |  |  |
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

</details>

## Spell saves summary table

Damage is an estimated number of destroyed units to compare their effects. Area effect spells are assumed to target 5 units or 3 if selective. Subverting unit counts as double as it not only takes one unit out of enemy army, but also gives it to the casting wizard.

| # | name | cost | save | damage | comment |
| ----: | ---- | ----: | ----: | ----: | ---- |
| 22 | Petrify | 35 | **-2** | 1 |  |
| 46 | Confusion | **30** | **0** | 2 | cheaper version of possession |
| 53 | Vertigo | 25 | **-2** | 0.75 |  |
| 64 | Banish | 20 | -3 | 1 |  |
| 68 | Stasis | 250 | -5 |  |  |
| 73 | Creature Binding | 70 | -2 | 2 |  |
| 75 | Great Unsummoning | 1000 | -3 |  |  |
| 88 | Shatter | 12 | 0 | 0.75 |  |
| 89 | Warp Creature | 18 | -1 | 0.5 |  |
| 134 | Dispel Evil | 25 | -4 | 1 |  |
| 150 | Holy Word | 60 | -2 | 3 |  |
| 162 | Weakness | 5 | -2 | 0.5 |  |
| 165 | Black Sleep | **30** | -2 | 1 |  |
| 168 | Terror | 20 | 1 | 1.25 |  |
| 172 | Possession | **50** | -1 | 2 |  |
| 182 | Wrack | **60** | 1 | 2.5 |  |
| 187 | Black Wind | 200 | -1 |  |  |
| 192 | Word of Death | 40 | -5 | 1 |  |
| 194 | Death Spell | 50 | -2 | 5 |  |
| 199 | Death Wish | 500 | 0 |  |  |


