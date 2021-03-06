---
title: Mercenary (Smuggler)
category: unit
---

# Mercenary (Smuggler)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: infantry
  * Side: Independant units
  * Buildable unit: Yes
  * Role: Generic
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 1
  * Type: infantry

|Level |1    |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------|-----|----|----|----|----|----|----|----|----|----|
|Health|15000|1200|1400|1600|2340|2600|2860|3120|3380|3900|


### Training stats

|Level        |1                                  |2                                  |3                                  |4                                  |5                                  |6                                  |7                                  |8                                  |9                                  |10                                  |
|-------------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|------------------------------------|
|Training time|4s                                 |4s                                 |5s                                 |5s                                 |5s                                 |5s                                 |5s                                 |6s                                 |6s                                 |6s                                  |
|Training cost|50$                                |70$                                |90$                                |110$                               |130$                               |150$                               |170$                               |190$                               |210$                               |230$                                |
|Building     |[Barracks 1](smugglerBarracks.html)|[Barracks 2](smugglerBarracks.html)|[Barracks 3](smugglerBarracks.html)|[Barracks 4](smugglerBarracks.html)|[Barracks 5](smugglerBarracks.html)|[Barracks 6](smugglerBarracks.html)|[Barracks 7](smugglerBarracks.html)|[Barracks 8](smugglerBarracks.html)|[Barracks 9](smugglerBarracks.html)|[Barracks 10](smugglerBarracks.html)|


### Upgrading stats

  * Upgrade time: 0s

|Level               |1    |2    |3     |4     |5     |6      |7      |8      |9       |10      |
|--------------------|-----|-----|------|------|------|-------|-------|-------|--------|--------|
|Upgrade requirements|1500$|5000$|14000$|25000$|50000$|100000$|200000$|750000$|2000000$|4000000$|


### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Flying unit: No
  * Max speed: 20
  * Propensity to go around obstacles: 1
  * Rotation speed: 7.854
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

## Main attack : Smuggler

### Targeting

  * Attack shield border: No
  * Max attack range: 5
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * View range: 8

|Level             |1-4                                                                                                                                                                                                                                                                                                                                                                                                        |5-10                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Target preferences|**Turret (80)**, _Headquarters (70)_, Droideka (50), Flying infantry (50), Flying vehicle (50), Heavy infantry (50), Heavy vehicle (50), Infantry (50), Light vehicle (50), Other building (50), Ressource generator (50), Shield (50), Shield generator (50), Storage (50), Support troop (50), Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)|**Turret (80)**, _Headquarters (70)_, Droideka (50), Flying infantry (50), Flying vehicle (50), Heavy infantry (50), Heavy infantry hero (50), Heavy vehicle (50), Heavy vehicule hero (50), Infantry (50), Infantry hero (50), Light vehicle (50), Other building (50), Ressource generator (50), Shield (50), Shield generator (50), Storage (50), Support troop (50), Vehicule hero (50), Wall (1), Trap (0)|


### Shooting

  * Animation delay: 0
  * Charge time: 250ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 1s
  * Can shoot over walls: No
  * Reload time: 2s
  * Retargeting offset: 10
  * Self-centered targeting: No
  * Shot count: 3
  * Shot delay: 500ms
  * Target locking: No

|Level          |1   |2  |3  |4  |5  |6  |7  |8  |9  |10 |
|---------------|----|---|---|---|---|---|---|---|---|---|
|Damage per shot|1625|130|152|174|273|304|334|364|395|455|


### Projectile

|Level                       |1   |2  |3  |4  |5  |6  |7   |8   |9   |10  |
|----------------------------|----|---|---|---|---|---|----|----|----|----|
|Displayed damage per second |1500|120|140|160|252|280|308 |336 |364 |420 |
|Calculated damage per second|1300|104|121|139|218|243|267 |291 |316 |364 |
|Calculated damage per cycle |4875|390|456|522|819|912|1002|1092|1185|1365|


  * Cannons per sequence: 1
  * Shooting cycle duration: 3.750s
  * Directional: Yes
  * Is deflectable: Yes
  * Max speed: 18
  * Damage multipliers: **(100)**: Droideka, Flying infantry, Flying vehicle, Headquarters, Heavy infantry, Heavy infantry hero, Heavy vehicle, Heavy vehicule hero, Infantry, Infantry hero, Light vehicle, Other building, Ressource generator, Shield, Shield generator, Storage, Support troop, Trap, Turret, Vehicule hero, Wall
  * Pass through shield: No
  * Salvos: 3

## Internal stats

These stats internal to the system link different parts of data together.

  * Unit ID: Smuggler

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: generalpurpose_smg-ani
  * Audio attack: "sfx_attack_blasterrifle_1":25,"sfx_attack_blasterrifle_2":25,"sfx_attack_blasterrifle_3":25,"sfx_attack_blasterrifle_4":25
  * Audio death: "sfx_death_troop_1":10,"sfx_death_troop_2":10,"sfx_death_troop_3":10,"sfx_death_troop_4":10,"sfx_death_troop_5":10,"sfx_death_troop_6":10,"sfx_death_troop_7":10,"sfx_death_troop_8":30
  * Audio placement: "sfx_placement_troop_1":35,"sfx_placement_troop_2":35,"sfx_placement_troop_3":30
  * Bullet: fx_blaster_beam_y_sm
  * Bundle name: generalpurpose_smg-ani
  * Death animation: buffFireBurn:15
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: none
  * Gun position: "generalpurpose_smg_rig_MASTER_MOVER/generalpurpose_smg_rig_locator_gun":1
  * Hit spark: fx_blaster_hit_y_sm
  * Icon camera position: 8.56,9.58,10.6
  * Icon lookat position: 0.09,1.4,0.28
  * Max scale: 100
  * Muzzle flash: fx_blaster_flash_y_sm
  * Name: Smuggler
  * Spin speed: 0
  * Targeted type: ENEMIES

|Level                      |1   |2  |3  |4  |5  |6  |7  |8  |9  |10 |
|---------------------------|----|---|---|---|---|---|---|---|---|---|
|Displayed damage per second|1500|120|140|160|252|280|308|336|364|420|


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Max scale: No
  * Seeks target: Yes
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1     |2     |3     |4     |5     |6     |7     |8     |9     |10    |
|-----------|------|------|------|------|------|------|------|------|------|------|
|Order      |330801|330802|330803|330804|330805|330806|330807|330808|330809|330810|
|Point value|1     |1.200 |1.400 |1.600 |1.800 |2     |2.200 |2.400 |2.600 |3     |


