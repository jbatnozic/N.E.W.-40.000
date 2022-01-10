# Codex: Necrons

## Codex Special Rules

  ### Reanimation Protocols:
  At the start of each of Remove Casualties step, this unit's Reanimation Protocols are enacted if the unit suffered any
  casualties since the last time they were enacted.

  When a unit's Reanimation Protocols are enacted, each model in it that would now be removed from the battlefield as a
  casualty has a chance to Reanimate itself and return to battle. This is done in two steps:
  1. **Reactivation:** Roll a D6 for the model (this is a "Reactivation roll").
  On a 5+, the model is Reactivated - proceed to step 2. Otherwise, the model fails to Reanimate.
  2. **Reassembly:** Roll another D6 for the model (this is a "Reassembly roll"). If the result of the roll is higher than
  the model's Wounds characteristic, the model is successfully Reassembled and Reanimated. Otherwise, the model fails to Reanimate.

  Models that are successfully Reanimated are NOT removed during this Remove Casualties step, regain all lost wounds and 
  no longer count as having been destroyed or otherwise made a casualty. All the rest are removed as normal.
  
  Both Reactivation and Reassembly rolls are considered Reanimation Protocol rolls for purposes of other rules.
  
  Each time a unit's Reanimation Protocols are enacted, you can make rolls for all models with the same Wounds characteristic
  all at once, instead of individually, and determine after rolling which model each success (after both rolls) applies to.
  
  In addition, each time a unit's Reanimation Protocols are enacted, if ALL the models in it have been destroyed (that is, 
  the whole unit will be removed if all Reanimation Protocol rolls fail), this is considered a "Critical Reanimation".
  During a Critical Reanimation, all Reanimation Protocol rolls suffer a -1 penalty.
  
  A single Reanimation Protocol roll cannot be modified by more than +1 or -1 after all the modifiers are totalled.
  
  **\<OLD\>**
  the protocols are enacted as destroyed models begin to reassemble.
  
  Each time a unit's reanimation protocols are enacted, make Reanimation Protocol rolls for that unit by rolling a number of
  D6 equal to the combined Wounds characteristics of all the models in the unit that would now be removed as casualties. Each
  Reanimation Protocol roll of 5+ is put into a pool.
  
  If the number of dice in the pool is greater or equal to the Wounds characteristic of any of the reassembling models, do the
  following:
   - Select one of the reassembling models to be Reanimated with full wounds remaining.
   - Reduce the number of dice in that pool by a number equal to the Wounds characteristic of the Reanimated model.
   - Repeat this process until either there are no more reassembling models, or the number of dice remaining in the pool is less than the Wounds characteristic of any of the reassembling models.

  Then, if there is at least one die remaining in the pool and at least one remaining reassembling model, select one of the 
  reassembling models to be Reanimated with a number of wounds remaining equal to the number of dice remaining in the pool.
  
  Models that are successfully Reanimated are NOT removed during this Remove Casualties step (and their wounds are adjusted as 
  stated above) and no longer count as having been destroyed or otherwise made a casualty. All the rest are removed as normal.
  
  (???)A Reanimation Protocol roll can never be modified by more than -1 or +1.
  (???) WHAT IF THE WHOLE UNIT WAS DESTROYED?
  **\</OLD\>**
  
  ### Cold Hard Logic:
  This unit ignores the effects of "Panicking" and is never considered to have this status. However, if this unit would receive
  this status as a result of a failed Morale test, do the following:
   - If more than half (rounded down) of its starting number of models are still present on the battlefield (even if they were destroyed but haven't yet been removed as casualties), nothing happens.
   - Otherwise, the units phases out - remove it from the battlefield at the end of the current battle phase (it counts as destroyed but this doesn't cause strain to nearby friendly units).
  
  _Example: A unit of Necron Warriors, which counted 10 models at the start of the game, takes a Morale test and fails with a
  large enough margin to warrant gaining the Panicking status. If at least 6 models are still present, the unit simply ignores
  this status. But if only 5 or fewer models are present, it will phase out at the end of the battle phase. If the unit had 
  originally counted 15 models, it would need more than 7 (so at least 8) models in order to not phase out._
  
  ### Living Metal:
  At the start of your Command phase, each model in this unit regains 1 lost wound.
  
  ### Hardwired for Destruction:
  (TODO)
  
  ### Dimensional Translocation:
  \[Same as Deep Strike]

## Tomb World Attributes

## Weapons

### Qualities

**Gauss Weapon:** This weapon ignores the Puny Force rule. Each time an attack is made with this weapon, wound rolls of 61 or
more always successfully wound the target. A wound roll of 61 or more that would successfully wound the target anyway is instead
resolved with Armour Penetration increased by 1.

**Tesla Weapon:** Each time an attack is made with this weapon, an unmodified hit roll of 61 or more scores 2 additional hits.

**Particle Weapon:** When this weapon targets a unit within half range, or the bearer hasn't moved in the previous Movement phase,
double the number of shots the weapon makes.

### Ranged Weapons list

| WEAPON                        | RANGE |     TYPE     |  S | AP |   D  | QUALITIES
|-------------------------------|-------|--------------|----|----|------|--------------------------- 
| Atomiser beam                 |       |              |    |    |      | -
| Doomsday blaster (low power)  |       |              |    |    |      | -
| Doomsday blaster (high power) |       |              |    |    |      | -
| Gauss blaster                 |  30"  | Rapid Fire 1 |  5 | -1 |   1  | **Gauss weapon**
| Gauss destructor              |  36"  | Heavy 1      |    |    |      | **Gauss weapon**
| Gauss flayer                  |  24"  | Rapid Fire 1 |  4 |  0 |   1  | **Gauss weapon**
| Gauss reaper                  |  12"  | Assault 2    |  5 | -1 |   1  | **Gauss weapon**
| Tesla cannon                  |  30"  | Heavy 3      |  6 |  0 |   1  | **Tesla weapon**
| Tesla carbine                 |  24"  | Assault 2    |  5 |  0 |   1  | **Tesla weapon**

### Melee Weapons list

| WEAPON                     |  TYPE |   S  | AP |  D  | QUALITIES
|----------------------------|-------|------|----|-----|--------------------------- 
| War Scythe                 | Melee | User | -8 | Inf | -

## Unit Datasheets

### \[HQ] Royal Warden

Note: The role of this model is unclear under the new core rules

---

### \[HQ] Skorpekh Lord

| NAME                     | PTS |  M  | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|-----|----|----|----|---|---|---|---|---|---|----|------
| Skorpekh Lord            | 200 |  8" | 4" |  7 |  8 | 6 | 6 | 6 | 5 | ? | * | 3+ | 50mm 

This unit contains one Skorpekh Lord, who is equipped with an Enmitic annihilator, (?) claw and a Hyperphase harvester.

**FACTION KEYWORDS:** NECRONS, DESTROYER CULT, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CHARACTER, CORE, SKORPEKH LORD

#### > SPECIAL RULES:
- TODO
- **Living Metal**
- **Hardwired for Destruction**

#### > OPTIONS:
- TODO

---

### \[HQ] Lokhust Lord

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Lokhust Lord             | 155 | 8" | 4" |  6 |  8 | 5 | 6 | 6 | 4 | ? | * | 3+ | 60mm 

This unit contains one Lokhust Lord, who is equipped with a Staff of Light.

**FACTION KEYWORDS:** NECRONS, DESTROYER CULT, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CHARACTER, CORE, FLY, LOKHUST LORD

#### > SPECIAL RULES:
- TODO
- **Living Metal**
- **Hardwired for Destruction**

#### > OPTIONS:
- This model's Staff of Light can be replaced with one of the following: 1 Hyperphase sword; 1 Voidblade; 1 Warscythe.
- TODO

---

### \[HQ] Lesser Lord

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Lesser Lord              | 105 | 6" | 4" |  6 |  8 | 5 | 5 | 4 | 3 | ? | * | 3+ | 32mm 

This unit contains one Lesser Lord, who is equipped with a Staff of Light.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CHARACTER, CORE, NOBLE, LESSER LORD

#### > SPECIAL RULES:
- TODO
- **The Lord's Will:** (TODO)

#### > OPTIONS:
- This model's staff of light can be replaced with one of the following: 1 hyperphase sword; 1 void blade; 1 warscythe.
- This model can be equipped with 1 resurrection orb.

---

### \[HQ] Overlord

---

### \[HQ] Technomancer

---

### \[HQ] Psychomancer

---

### \[HQ] Chronomancer

---

### \[HQ] Plasmancer

---

### \[Troop] Necron Warriors

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Necron Warrior           |  19 | 5" | 4" |  5 |  7 | 4 | 4 | 1 | 1 | 2 | * | 4+ | 32mm 

This unit contains 10 Necron Warriors. It can contain up to 10 additional Warriors. Every model 
is equipped with a Gauss flayer.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CORE, NECRON WARRIORS

#### > SPECIAL RULES:
- TODO

#### > OPTIONS:
- Any number of models may replace their Gauss flayer with a Gauss reaper.

---

### \[Troop] Immortals

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Immortal                 |  28 | 5" | 4" |  5 |  7 | 4 | 5 | 2 | 2 | 2 | * | 3+ | 32mm 

This unit contains 5 Immortals. It can contain up to 5 additional Immortals. Every model 
is equipped with a Gauss blaster.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CORE, IMMORTALS

#### > SPECIAL RULES:
- TODO

#### > OPTIONS:
- Any number of models may replace their Gauss flayer with a Tesla carbine.

---

### \[Elite] Canoptek Reanimator

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Canoptek Reanimator      | 110 | 8" | 4" |  4 |  5 | 6 | 6 | 7 | 4 | ? | * | 3+ | 60mm 

This unit contains 1 Canoptek Reanimator. It is equipped with 2 Atomiser beams and reanimator's claws.

**FACTION KEYWORDS:** NECRONS, CANOPTEK, \<DYNASTY\>

**KEYWORDS:** VEHICLE, CANOPTEK REANIMATOR

| WEAPON                        | RANGE |     TYPE     |  S | AP | D | QUALITIES
|-------------------------------|-------|--------------|----|----|---|--------------------------- 
| Atomiser beam                 |  12"  | Assault 3    |  6 | -2 | 1 | -

| WEAPON                     |  TYPE |   S  | AP |  D  | QUALITIES
|----------------------------|-------|------|----|-----|--------------------------- 
| Reanimator's claws         | Melee | User | -2 | D2  | -

#### > SPECIAL RULES:
- **Living Metal**
- **Explodes** (TODO)
- **(?) (Aura):**

#### > OPTIONS:
(none)

---

### \[Elite] Lychguard

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Lychguard                |  42 | 5" | 4" |  5 |  7 | 5 | 5 | 2 | 3 | ? | * | 3+ | 32mm 

This unit contains 5 Lychguard. It can contain up to 5 additional Lychguard. Every model 
is equipped with a Warscythe.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CORE, LYCHGUARD

---

### \[Elite] Deathmarks

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Deathmarks               |  25 | 5" | 4" |  5 |  8 | 4 | 4 | 1 | 1 | 2 | * | 3+ | 32mm 

This unit contains 5 Deathmarks. It can contain up to 5 additional Deathmarks. Every model 
is equipped with a Synaptic disintegrator.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CORE, HYPERSPACE HUNTER, DEATHMARKS

| WEAPON                        | RANGE |     TYPE     |  S | AP |   D  | QUALITIES
|-------------------------------|-------|--------------|----|----|------|--------------------------- 
| Synaptic disintegrator        |  36"  | Heavy 1      |  5 | -2 |  D2  | Attacks made with this weapon ignore the "Look Out, Sir" rule.

#### > SPECIAL RULES:
- **Deep Strike**

#### > OPTIONS:
(none)

---

### \[Elite] Flayed Ones

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Flayed One               |  19 | 5" | 4" |  5 |  1 | 4 | 4 | 1 | 3 | 4 | * | 4+ | 32mm 

This unit contains 5 Flayed Ones. It can contain up to 15 additional Flayed Ones. Every model 
is equipped with a Flayer claws.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** INFANTRY, CORE, FLAYED ONES

| WEAPON                     |  TYPE |   S  | AP |  D  | QUALITIES
|----------------------------|-------|------|----|-----|--------------------------- 
| Flayer claws               | Melee | User | -1 |  1  | Wounds rolls of 61 or more with this weapon are resolved with AP improved by 1.

#### > SPECIAL RULES:
- **Deep Strike**

- **Flesh Hunger:** Increase this unit's Move characteristic by 1 whenever it's moving towards
an enemy non-VEHICLE unit (the bonus lasts until the end of the action). Each time a model in 
this unit makes a melee attack against an enemy non-VEHICLE unit, a hit roll of 61 or more
scores 1 additional hit.

- **Terrifying Foes (Aura):** TODO

#### > OPTIONS:
(none)

---

### \[Elite] Skorpekh Destroyers

| NAME                     | PTS |  M  | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|-----|----|----|----|---|---|---|---|---|---|----|------
| Skorpekh Destroyer       |  52 |  8" | 4" |  5 |  7 | 5 | 5 | 3 | 3 | ? | * | 3+ | 50mm 

This unit contains 3 Skorpekh Destroyers. It can contain up to 3 additional Skorpekh Destroyers. 
Every model is equipped with Hyperphase threshers.

**FACTION KEYWORDS:** NECRONS, DESTROYER CULT, \<DYNASTY\>

**KEYWORDS:** INFANTRY, SKORPEKH DESTROYERS

| WEAPON                     |  TYPE |   S  | AP |  D  | QUALITIES
|----------------------------|-------|------|----|-----|--------------------------- 
| Hyperphase reap-blade      | Melee |  +2  | -3 |  3  | -
| Hyperphase threshers       | Melee | User | -2 |  2  | Each time the bearer fights, it makes 1 additional attack with this weapon.

#### > SPECIAL RULES:
- **Hardwired for Destruction**
- TODO

#### > OPTIONS:
- One model in the unit, or two if the unit contains 6 models, may replace their Hyperphase
threshers with a Hyperphase reap-blade.

---

### \[Elite] Canoptek Plasmacyte

| NAME                     | PTS |  M  | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|-----|----|----|----|---|---|---|---|---|---|----|------
| Canoptek Plasmacyte      |  25 |  8" | 4" |  2 |  - | 4 | 4 | 2 | 1 | ? | * | 3+ | 28mm 

This unit contains 1 Canoptek Plasmacyte.

**FACTION KEYWORDS:** NECRONS, CANOPTEK, \<DYNASTY\>

**KEYWORDS:** BEAST, FLY, CANOPTEK PLASMACYTE

#### > SPECIAL RULES:
- TODO

#### > OPTIONS:
(none)

---

### \[Elite] Canoptek Spyders

| NAME                     | PTS |  M  | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|-----|----|----|----|---|---|---|---|---|---|----|------
| Canoptek Spyder          |  80 |  7" | 4" |  4 |  5 | 6 | 6 | 5 | 5 | ? | * | 3+ | 60mm flying base 

This unit contains 1 Canoptek Spyder. It can contain up to 2 additional Canoptek Spyders. 
Every model is equipped with Automaton claws.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** MONSTER, FLY, CANOPTEK, CANOPTEK SPYDER

| WEAPON                        | RANGE |     TYPE     |  S | AP | D | QUALITIES
|-------------------------------|-------|--------------|----|----|---|--------------------------- 
| Particle beamer               |  18"  | Assault 3    |  5 |  0 | 1 | **Particle Weapon**

| WEAPON                     |  TYPE |   S  | AP |  D  | QUALITIES
|----------------------------|-------|------|----|-----|--------------------------- 
| Automaton claws            | Melee | User | -2 |  2  | Each time an attack is made with this weapon against a VEHICLE, the hit roll and wound roll gain Advantage.

#### > SPECIAL RULES:
- TODO
- **Living Metal**
- **Scarab Hive:** At the start of your Morale phase, for each model with this ability, select one friendly \<DYNASTY\> CANOPTEK SCARAB SWARM unit within 6" of that model. If the selected unit is below its starting strength, one model is returned to that unit - set it up with full wounds remaining in Unit Coherency with its unit and as close as possible to the Canoptek Spyder, but not within Engagement Range of enemy models. If this is not possible, then the model cannot be returned.
- **Fabricator Claw Array (only if equipped):** This model's "Scarab Hive" ability can target any NECRONS \<DYNASTY\> INFANTRY or NECRONS \<DYNASTY\> VEHICLE unit (other than AIRCRAFT or TITANIC), in which case its range is reduced to 3". If an INFANTRY unit is targeted, a successful Reassembly roll is required (as if the unit's reanimation protocols were enacted, though none of the modifiers apply), or nothing happens. If a VEHICLE unit is targeted, its effect is instead that the VEHICLE regains up to D3 lost wounds.
- **Gloom Prism (only if equipped):** In your opponent's Psychic phase, the bearer's unit can attempt to deny one psychic power as if it were a PSYKER.

#### > OPTIONS:
- Any number of models can each be equipped with 2 Particle beamers (+15 pts total (not per Particle beamer)).
- Any number of models can each be equipped with 1 Fabricator claw array (+15 pts).
- Any number of models can each be equipped with 1 Gloom prism (+10 pts).

---

### \[Fast Attack] Canoptek Scarab Swarms

| NAME                     | PTS |  M  | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|-----|----|----|----|---|---|---|---|---|---|----|------
| Scarab Swarm             |  22 | 10" | 4" |  3 |  - | 3 | 3 | 4 | 4 | 3 | * | 6+ | 40mm 

This unit contains 3 Scarab Swarms. It can contain up to 6 additional Scarab Swarms. Every model 
is equipped with Feeder mandibles.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** SWARM, FLY, CANOPTEK SCARAB SWARMS

| WEAPON                     |  TYPE |   S  | AP |  D  | QUALITIES
|----------------------------|-------|------|----|-----|--------------------------- 
| Feeder mandibles           | Melee | User |  0 |  1  | -

#### > SPECIAL RULES:
- TODO

#### > OPTIONS:
(none)

---

### \[Fast Attack] Canoptek Wraiths

| NAME                     | PTS |  M  | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|-----|----|----|----|---|---|---|---|---|---|----|------
| Canoptek Wraith          |  55 | 10" | 4" |  5 |  5 | 4 | 5 | 3 | 4 | ? | * | 4+ | 50mm 

This unit contains 1 Canoptek Wraith. It can contain up to 5 additional Canoptek Wraiths. 
Every model is equipped with Vicious claws.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:** BEAST, CANOPTEK, CANOPTEK WRAITHS

| WEAPON                        | RANGE |     TYPE     |  S | AP | D | QUALITIES
|-------------------------------|-------|--------------|----|----|---|--------------------------- 
| Particle caster               |  12"  | Pistol 2     |  5 |  0 | 1 | **Particle Weapon**
| Transdimensional beamer       |  12"  | Assault 1    |  4 | -2 | 2 |

| WEAPON                     |  TYPE |   S  | AP |  D  | QUALITIES
|----------------------------|-------|------|----|-----|--------------------------- 
| Vicious claws              | Melee |  +2  | -2 |  2  | -
| Whip coils                 | Melee | User | -1 |  1  | Each time an attack is made with this weapon, make 2 hit rolls instead of 1.

#### > SPECIAL RULES:
- **Wraith Form:** Models in this unit have a 4+ invulnerable save. In addition, whenever this unit moves for any reason, models in it
can move horizontally through models and terrain features (but they cannot finish a move on top of another model or its base).
- TODO

#### > OPTIONS:
- Any number of models can each be equipped with one of the following: 1 Particle caster (+5 pts); 1 Transdimensional beamer (+5 pts).
- Any number of models can each have their Vicious claws replaced with Whip coils (free).

---

### \[Heavy Support] Lokhust Destroyers

| NAME                     | PTS |  M | CB | MS | BS | S | T | W | A | I | N | Sv | Base 
|--------------------------|-----|----|----|----|----|---|---|---|---|---|---|----|------
| Lokhust Destroyer        |  70 | 8" | 4" |  5 |  8 | 4 | 5 | 3 | 2 | ? | * | 3+ | 60mm 

This unit contains 1 Lokhust Destroyer. It can contain up to 5 additional Lokhust Destroyers.
Every model is equipped with a Gauss destructor.

**FACTION KEYWORDS:** NECRONS, \<DYNASTY\>

**KEYWORDS:**: INFANTRY, CORE, FLY, DESTROYER CULT, LOKHUST DESTROYERS

| WEAPON                        | RANGE |     TYPE     |  S | AP |   D  | QUALITIES
|-------------------------------|-------|--------------|----|----|------|--------------------------- 
| Synaptic disintegrator        |  36"  | Heavy 1      |  5 | -2 |  D2  | Attacks made with this weapon can ignore the "Look Out, Sir" rule.

#### > SPECIAL RULES:
- **Hardwired for Destruction**
- **Relentless*

#### > OPTIONS:
(none)

---

### \[Heavy Support] Lokhust Heavy Destroyers

---

### \[Heavy Support] Canoptek Doomstalker
