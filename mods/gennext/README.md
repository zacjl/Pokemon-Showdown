Generation NEXT!
========================================================================

Manifesto
------------------------------------------------------------------------

The goal of NEXT is to improve the diversity of the OU metagame by only doing
things that could plausibly be done between gens.

Specifically, the core rules of NEXT are:

1. no base stat changes
2. no removing from movepools
3. no removing from ability distribution
4. no typing changes (except on formes)
5. no buffing OU mons, except maybe tiny buffs to mons at the bottom of OU
6. no doing things that make zero sense flavor-wise

What's left is mainly changes to how abilities and moves work, which is
most of what NEXT is about.

A good example is what Game Freak did by giving Ditto the Imposter ability.
This gave a Ditto a role in OU, while still making sense flavor-wise, and
without removing anything it used to have.

A good example of what NEXT changes is Cherrim. We have taken an interesting
idea (ability designed for Sunny Day support) and made it viable in OU.

This approach is in sharp contrast to many mods that do change many things on
NEXT's "don't change" list. The result is a metagame that feels a lot like
a new generation: existing OU threats stay mostly the same, but many new
threats and strategies are introduced.

And yes, we know that "no base stat changes" has been broken in Gen 6. We're
still not doing it, because it's hard to constrain and hard to keep track of.

Recent changes
------------------------------------------------------------------------

A changelog for NEXT is available here:

https://github.com/Zarel/Pokemon-Showdown/commits/master/mods/gennext



Generation NEXT changes
------------------------------------------------------------------------

Miscellaneous

- Stealth Rock now does 1/4 damage against Flying-types, and 1/8 damage against
  everything else
  - Rock Throw now removes Stealth Rock from your side of the field

- Pokemon now thaw from freeze at the end of the second turn

- Confusion now deals 30 base power damage every attack, but does not stop
  the attack. It now lasts 3-5 turns

- Every Hidden Ability is released

Weather

- Weather moves have +1 priority

- Forecast makes weather moves last forever. Cherrim, Phione, Cryogonal, and
  Probopass make Sunny Day, Rain Dance, Hail, and Sandstorm last forever,
  respectively

Hail
- Silver Wind, Ominous Wind, and Avalanche deal 1.5x damage in Hail
- Snow Cloak decreases damage taken by 12.5%, increased to 25% in Hail
- Ice Body heals for 1/16 each turn. In hail, it has a 30% chance to freeze
  when hit by a contact move
- Flame Body, Marvel Scale, and Thick Fat grant immunity to Hail damage

Pokemon-specific changes
------------------------------------------------------------------------

- Cherrim-Sunshine is Grass/Fire type
  - Flower Gift now only boosts SpD, but if Sunny Day is used while Cherrim is
    active, the next switch-in also receives +1 SpD
- Cherrim, Phione, Cryogonal, and Probopass make Sunny Day, Rain Dance, Hail,
  and Sandstorm last forever, respectively
- Floette-Eternal-Flower is released
- Genesect's secondary type becomes the same as its Drive immediately after
  switching in. Download will not activate for Genesect unless it holds a Drive
- Kangaskhan-Mega - Parental Bond does half damage on both hits, but confers
  perfect accuracy like all multi-hit moves (see move changes below)
- Meloetta's SpA and Atk EVs, boosts, and Modest/Adamant and Jolly/Timid
  natures are swapped by Relic Song. The move has +1 priority, 60 base power,
  and no secondary effect

Learnset:

- Ambipom, Mr. Mime, and Spinda get Sketch as an egg move, allowing them to
  use exactly one move not normally in their learnset
- Ampharos, Lanturn, and Lumineon get Tail Glow
- Azumarill gets Belly Drum with no incompatibilities
- Butterfree, Beautifly, Masquerain, and Mothim get Hurricane
- Galvantula gets Zap Cannon
- Masquerain gets Surf
- Mantine gets Recover, Whirlwind, Baton Pass, Wish, Soak, Lock-On, Acid Spray,
  Octazooka, and Stockpile
- Meloetta gets Fiery Dance
- Roserade gets Sludge
- Rotom formes learn more things:
  - Rotom-Wash: Bubble Beam
  - Rotom-Fan: Hurricane, Twister
  - Rotom-Frost: Frost Breath
  - Rotom-Heat: Heat Wave
  - Rotom-Mow: Magical Leaf
- Scolipede and Steelix get Coil
- Spinda gets V-Create, Superpower, Close Combat, Overheat, Leaf Storm, and
  Draco Meteor.
- Virizion gets Horn Leech
- Zoroark gets Ice Beam, Giga Drain, Earthquake, Stone Edge, Superpower, and
  X-Scissor

New mechanic: Signature Pokémon

- Certain moves have a Signature Pokémon associated with them. A move will
  deal 1.5x its usual damage when used by its Signature Pokémon
  - Flareon: Fire Fang 
  - Walrein: Ice Fang
  - Luxray: Thunder Fang
  - Drapion: Poison Fang
  - Seviper: Poison Tail
  - Muk: Sludge
  - Weezing: Smog
  - Rapidash: Flame Charge
  - Darmanitan: Flame Wheel
  - Eelektross: Spark
  - Hitmontop: Triple Kick
  - Kingdra: Bubble Beam
  - Galvantula: Electroweb
  - Skarmory: Steel Wing
  - Beautifly: Giga Drain
  - Glaceon: Icy Wind
  - Swampert: Mud Shot
  - Kyurem: Glaciate
  - Octillery: Octazooka
  - Serperior: Leaf Tornado
  - Weavile: Ice Shard
  - Sharpedo: Aqua Jet
  - Hitmonchan: Mach Punch
  - Banette: Shadow Sneak
  - Masquerain: Surf
  - Snorlax: Snore
  - Persian: Slash
  - Unown: Hidden Power
  
Abilities:

- Crawdaunt gets Tough Claws instead of Adaptability (this is because of a nerf
  to Adaptability)
- Vespiquen gets Swarm

- Starters get a new ability option
  - Venusaur: Leaf Guard
  - Charizard: Flame Body
  - Blastoise: Shell Armor
  - Meganium: Harvest
  - Typhlosion: Magma Armor
  - Feraligatr: Strong Jaw
  - Sceptile: Limber
  - Blaziken: Reckless
  - Swampert: Hydration
  - Torterra: Weak Armor
  - Infernape: No Guard
  - Empoleon: Ice Body
  - Serperior: Own Tempo
  - Emboar: Sheer Force
  - Samurott: Technician
  - Chesnaught: Battle Armor
  - Delphox: Magic Guard
  - Greninja: Pickpocket

New mechanic: Intrinsics

- Pokémon that previously get Levitate are now immune to Ground intrinsically,
  although Mold Breaker still bypasses this immunity. Instead, many of them get
  new abilities in addition to their Ground immunity:
  - Azelf: Steadfast
  - Bronzong: Heatproof
  - Claydol: Filter
  - Cryogonal: Ice Body
  - Eelektross: Poison Heal
  - Flygon: Compoundeyes, Sand Rush
  - Hydreigon: Sheer Force
  - Mesprit: Serene Grace
  - Mismagius: Cursed Body
  - Rotom (all formes): Trace
  - Unown: Shadow Tag
  - Uxie: Synchronize
  - Weezing: Aftermath

Moves
------------------------------------------------------------------------

General Changes

- Weather moves have +1 priority (Hail, Rain Dance, Sandstorm, Sunny Day)
- Moves which originally had perfect accuracy now have 90 base power (Aerial
  Ace, Aura Sphere, Clear Smog, Disarming Voice, Feint Attack, Magical Leaf
  Magnet Bomb, Shadow Punch, Shock Wave, Swift)
- Multi-hit moves all have perfect accuracy (Arm Thrust, Barrage, Beat Up, Bone
  Rush, Bonemerang, Bullet Seed, Comet Punch, Double Hit, Double Kick, Double
  Slap, Dual Chop, Fury Attack, Fury Swipes, Gear Grind, Icicle Spear, Pin
  Missile, Power Gem, Rock Blast, Spike Cannon, Tail Slap, Tri Attack, Triple
  Kick, Twineedle, Water Shuriken, Wing Attack)
- Moves with a charge turn have modified base power, always crit, have perfect
  accuracy, remove Protection and Substitute before hitting, and have one other
  change depending on the move:
  - Bounce: 30% paralysis, 60 bp
  - Dig: 100% -1 Def, 60 bp
  - Dive: 100% -1 Def, 60 bp
  - Fly: 100% -1 Def, 60 bp
  - Freeze Shock: 100% paralysis, 95 bp
  - Ice Burn: 100% burn, 95 bp
  - Phantom Force: 100% -1 Def, 60 bp
  - Razor Wind: 100% confusion, 60 bp
  - Shadow Force: 100% Ghost-Curse, 40 bp
  - Skull Bash: +1 Def, +1 SpD, +1 accuracy on charge turn, 70 bp
  - Sky Attack: 100% -1 Def, 95 bp
  - Sky Drop: 100% -1 Def, 60 bp
  - SolarBeam: heal 50% on charge turn, 80 bp
- Recharge moves are similarly buffed: they have 100 base power, always crit,
  and they only recharge if they KO (Blast Burn, Frenzy Plant, Giga Impact,
  Hydro Cannon, Hyper Beam, Roar of Time, Rock Wrecker)
- All other moves' accuracy is rounded up to the nearest multiple of 10%,
  apart from:
  - Charge Beam (100%)
  - Fire Blast (80%)
  - Focus Blast (30%)
  - Muddy Water (100%)
  - Smog (100%)
  - Steel Wing (100%)
  - Rock Slide (100%)
  - Rock Throw (100%)
  
- Bone moves are not affected by immunities (you can hit a bird with a bone)
  (Bone Club, Bone Rush, Bonemerang)
- Elemental fang moves have a 20% chance to apply their respective status and
  a 30% chance to flinch (Fire Fang, Ice Fang, Thunder Fang)
- Protection does not protect Substitutes (Detect, King's Shield, Mat Block,
  Protect, Quick Guard, Spiky Shield, Wide Guard)
- Sound-based moves are no longer affected by immunities (ghosts can hear
  things) (Boomburst, Echoed Voice (only the first hit), Hyper Voice, Relic
  Song, Round, Snore, Uproar)
- Acid and Acid spray are not affected by immunities
- Ancient Power, Silver Wind, and Ominous Wind have a 100% chance of raising
  one of Def/SpA/SpD/Spe at random, rather than a 10% chance of raising every
  stat
- Attack Order, Drill Peck, Leaf Blade, and Needle Arm have 100 base power
- Avalanche, Ominous Wind, and Silver Wind deal 1.5x damage in Hail
- Cut and Rock Smash have 50 base power and a 100% chance to give the target -1
  Def
- Defend Order and Heal Order now have +1 priority
- Double Team and Minimize are nerfed:
  - Double Team takes 25% of user's max HP (like Substitute)
  - Minimize only gives +1 evasion
- Draining Kiss and Parabolic Charge have 40 base power and give -1 SpA, -1
  Atk to the target and +1 SpA, +1 Atk to the user
- Explosion and Self Destruct have 250 and 200 base power, respectively,
  always crit, and have perfect-accuracy
- Power Gem and Wing Attack have 40 base power and hit twice, like Dual Chop
- Rapid Spin and Rock Throw are buffed. They remove hazards before effects like
  Rocky Helmet, etc., and double in power if they remove hazards. Additionally:
  - Rapid Spin has 30 base power
  - Rock Throw removes Stealth Rock from the user's side of the field,
    and has 100% accuracy
- Scald and Steam Eruption no longer have their damage affected by weather.
  Instead, they have a 60% chance to burn in sun
- Steamroller and Stomp have 100 Base Power and perfect accuracy to reflect
  their thematic status as counters to Minimize

Specific Changes

- Autotomize gives +3 Speed
- Bide gives its user Endure (the user survives all move damage with at least 1
  HP) for its duration. The move fails if the user has 1 HP when it's used, or
  if the user's last move used was Bide.
- Blizzard has a 30% chance to freeze
- Blue Flare has a 30% chance to burn
- Bone Rush has 20 power because it should never be viable
- Bubble Beam has a 30% chance to give the target -1 Spe
- Close Combat gives -2 to Def and SpD
- Dizzy Punch has 90 base power and a 50% chance to confuse
- Echoed Voice has 80 base power, hits once, and then, 2 turns later, hits
  again for 80 base power. It's like Doom Desire, except it still hits
  that first time
- Egg Bomb has 40 base power and always crits
- Electroweb has 60 base power
- Flame Charge has 60 base power
- Fire Blast has a 20% chance to burn and 80% accuracy
- Focus Blast has 30% accuracy
- Glaciate has 80 base power
- High Jump Kick has 100 base power
- Icy Wind has 60 base power
- Leaf Tornado has 75 base power and a 100% to give the target -1 Accuracy
- Leech Life has 75 base power
- Mud Shot has 60 base power
- Muddy Water has 85 base power and 100% accuracy
- Night Daze displays as a random non-Status move in the copied Pokémon's
  moveset if Illusion is not broken
- Octazooka has 75 base power and a 100% to give the target -1 Accuracy
- Poison Fang has 65 base power, a 100% chance to apply toxic poison, and a 30%
  chance to flinch
- Poison Tail has 60 base power and a 60% to apply toxic poison
- Psycho Cut has 90 base power
- Relic Song has +1 priority, 60 base power, and no secondary effect; it swaps
  Meloetta's Atk and SpA EVs, boosts, and certain natures (see Meloetta)
- Sacred Sword has 95 base power
- Shadow Ball has 90 base power and a 30% chance to give the target -1 SpD
- Shell Smash breaks the user's Shell Armor (the ability will be removed)
- Slash has 60 base power and a 30% chance to give the target -1 Def
- Sludge has 60 base power and a 100% chance to poison
- Smog has 75 base power, a 100% chance to poison, and 100% accuracy
- Snore has 100 base power
- Surf has a 10% chance to give targets hit -1 Spe
- Steel Wing has 60 base power, a 100% chance to give +1 Def, and 100% accuracy
- Substitutes increase accuracy against them to 100%
- Strength has a 30% chance to raise the user's Atk
- Twineedle has 50 base power
- Twister is Flying type, has 80 base power, and has a 30% chance to confuse
- Tri Attack hits 3 times and has 30 base power
- Withdraw gives +1 SpD in addition to Def

Abilities
------------------------------------------------------------------------

General Changes

- Aftermath and Cursed Body no longer require contact, and additionally:
  - Aftermath deals 1/3 of the foe's max hp
  - Cursed Body applies ghost-Curse to the foe instead
- Battle Armor, Magma Armor, Prism Armor, Shell Armor, and Weak Armor reduce
  incoming move damage by 1/10 of the user's max HP in addition to their normal
  effects (except for Weak Armor). Also:
  - Magma Armor also provides a one-time immunity to Water and Ice, after which
    it turns into Battle Armor
  - Shell Armor is removed upon using Shell Smash
  - Weak Armor only activates on the first hit after switch-in, and gives the
    user +1 Spe; its former effect is *replaced*
- Chlorophyll, Slush Rush, Sand Rush, and Swift Swim give a 1.5x speed buff
- Clear Body and White Smoke prevent all stat lowering
- Compound Eyes and Keen Eye grant 1.6x accuracy instead
- Cute Charm, Poison Point, and Static always activate on contact.
- Filter and Solid Rock reduce the damage of SE moves by 1/2
- Flare Boost, Guts, Quick Feet, and Toxic Boost halve damage from their
  respective statuses (burns for Flare Boost, Guts, and Quick Feet; poison for
  Guts, Quick Feet, and Toxic Boost)
- Own Tempo prevents lock-in from Outrage, Thrash, and Petal Dance
- Reckless and Rock Head always work with Life Orb
  
Specific Changes
  
- Adaptability boosts the power of non-STAB moves to 1.33x to instead of to
  STAB moves
- Download will not activate for Genesect unless it holds a Drive
- Flame Body, Marvel Scale, and Thick Fat grant immunity to Hail damage
- Flower Gift now only boosts Sp. Def, but if Sunny Day is used while Cherrim
  is active, the next switch-in also receives the SpD buff
- Gluttony allows a Pokémon to use a Berry twice
- Heatproof gives the user immunity to Fire and burns
- Ice Body heals for 1/16 each turn. In hail, it has a 30% chance to freeze
  when hit by a contact move
- Iron Fist gives a 1.33x boost to punching moves
- Multiscale decreases damage by 1/3 rather than 1/2
- Parental Bond does half damage on both hits, but confers
  perfect accuracy like all multi-hit moves
- Sand Veil gives 20% damage reduction in sand instead
- Shadow Tag only lasts one turn
- Slow Start only lasts 3 turns
- Speed Boost does not activate on turns Protect, Detect, Endure, etc
  are used
- Stench gives a 40% flinch chance
- Snow Cloak decreases damage taken by 12.5%, increased to 25% in Hail
- Swarm also halves damage taken from the user's weaknesses from its Flying
  type (if any, including from Stealth Rock)
- Telepathy also Imprisons on switch-in
- Thick Fat also reduces damage from Fighting by 1/2
- Truant will only activate if a move succeeds (e.g. not if it misses, fails,
  or is Protected against), and will heal the user by 33% during its Truant
  turn
- Victory Star gives 1.5x accuracy (but only for the user)
- Water Veil decreases damage taken by 12.5%, increased to 25% in Rain

Items
------------------------------------------------------------------------

- Life Orb behaves more consistently as normal recoil. Reckless will boost
  every move if Life Orb is held, and Rock Head will negate Life Orb recoil

- Stick is also used as a placeholder for several items:

  - Berry Shell gives Shuckle a 50% boost to Defense and Sp. Def.

  - Gossamer Wing, an item for Quiver Dancers (except Smeargle). It makes
    them take half damage from Rock, Ice, and Electric moves if they are
    Flying type, prevents them from taking double SR damage, heals 1/16
    after using a Status move, and makes Twister do 1.5x Damage

  - Strange Orb gives Unown 2x SpA, SpD, and Spe, and changes its type to the
    type of its Hidden Power

- Wide Lens now grants 1.3x accuracy

- Zoom Lens now grants 1.6x accuracy

New: Type-specific items:

- Big Root: acts like Leftovers + Shell Bell for Grass types

- Black Sludge: heals 1/8 per turn for pure Poison types

- Focus Band: breaks on first hit, but allows pure Fighting types to survive
  that hit with 1 HP (so basically it'd be a Focus sash that stays intact
  after residual damage); does nothing for other Pokémon

- Wise Glasses: 1.2x for pure Psychic types

- Muscle Band: Atk boost increased to 1.2x for pure Fighting types

Bans:
------------------------------------------------------------------------

- The OU banlist (i.e. Pokémon considered Uber) is now:
  - Every Pokémon with over 600 BST except Slaking, Regigigas, and Hoopa-Unbound
  - Deoxys (all formes)
  - Darkrai
  - Shaymin-Sky
- The following clauses are in effect:
  - OHKO Clause
  - Sleep Clause
  - Soul Dew is banned

Specifically, differences from regular OU:

- unbanned: Aegislash, Blaziken, Genesect, Landorus, Gengarite, Kangaskhanite,
  Lucarionite, Mawilite, Salamencite
- banned: Hoopa-Unbound, Kyurem, Kyurem-Black
- There is no Moody Clause or Evasion Clause
