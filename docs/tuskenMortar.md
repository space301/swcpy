---
title: "bld_title_tuskenMortar" (tuskenMortar)
category: building
---

# "bld_title_tuskenMortar" (tuskenMortar) — version 1099

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: turret
  * Cross credits: 0
  * Side: Tusken Raiders
  * Force reticle when targeted: No
  * Hide if locked: Yes
  * Produce: 0
  * Spawn protect: 5
  * Type: turret

|Level          |1   |2   |3    |4    |5     |6     |7     |8     |9      |10     |
|---------------|----|----|-----|-----|------|------|------|------|-------|-------|
|Cross materials|3000|6000|30000|90000|180000|480000|600000|900000|2400000|3600000|
|Cross time     |1m  |2m  |3m   |4m   |5m    |6m    |7m    |8m    |9m     |10m    |
|Health         |5000|7500|9000 |12000|14500 |17000 |19500 |22000 |24500  |27000  |
|Max quantity   |2   |4   |6    |8    |10    |12    |14    |16    |18     |20     |
|Time           |1m  |30m |4h   |16h  |1d12h |2d12h |4d    |6d    |1w1d   |1w3d   |


### Training stats

|Level   |1-3                                |4                                  |5                                  |6                                  |7                                                  |8                                                  |9                                                  |10                                                  |
|--------|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|---------------------------------------------------|---------------------------------------------------|---------------------------------------------------|----------------------------------------------------|
|Building|[Tusken Raider HQ 3](tuskenHQ.html)|[Tusken Raider HQ 4](tuskenHQ.html)|[Tusken Raider HQ 5](tuskenHQ.html)|[Tusken Raider HQ 6](tuskenHQ.html)|["bld_title_tuskenHQLocked" 7](tuskenHQLocked.html)|["bld_title_tuskenHQLocked" 8](tuskenHQLocked.html)|["bld_title_tuskenHQLocked" 9](tuskenHQLocked.html)|["bld_title_tuskenHQLocked" 10](tuskenHQLocked.html)|


### Upgrading stats

  * Upgrade requirements: Nothing

### Movement stats

  * Acceleration: 0
  * Max speed: 0
  * Unit size on map: 2x2

## Turret attack : Empire Mortar Turret


### Targeting

  * Turret max attack range: 11
  * Turret min attack range: 4
  * Turret target preference strength: 90
  * Turret view range: 10

### Shooting

  * Turret time between start of clip and first shot: 1.500s
  * Turret clip retargeting: No
  * Turret gun shooting sequence: 1
  * Turret impact delay: 1s
  * Turret can shoot over walls: Yes
  * Turret time between end of clip and start of clip: 1.500s
  * Turret shot count: 1
  * Turret time between shots: 1ms

|Level                 |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------|----|----|----|----|----|----|----|----|----|----|
|Turret damage per shot|1050|1575|1890|2520|3045|3360|3675|3990|4305|4725|


  * Turret attack splash damage percentages: 100,30,20,10,10

|Level                                     |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------------------------------------------|----|----|----|----|----|----|----|----|----|----|
|Turret displayed damage per second        |350 |525 |630 |840 |1015|1120|1225|1330|1435|1575|
|Turret attack calculated damage per second|350 |525 |630 |840 |1015|1120|1225|1330|1435|1575|
|Turret attack calculated damage per clip  |1050|1575|1890|2520|3045|3360|3675|3990|4305|4725|


  * Turret attack cannons per sequence: 1
  * Turret attack cliptime: 3s
  * Turret attack directional: No
  * Turret attack is deflectable: No
  * Turret attack max speed: 4
  * Turret attack damage multipliers: **(100)**: Turret attack droideka, Turret attack headquarters, Turret attack other building, Turret attack ressource generator, Turret attack shield, Turret attack shield generator, Turret attack storage, Turret attack support troop, Turret attack trap, Turret attack turret, Turret attack wall, **(80)**: Turret attack infantry, Turret attack infantry hero, **(60)**: Turret attack heavy infantry, Turret attack heavy infantry hero, **(50)**: Turret attack light vehicle, Turret attack vehicule hero, **(25)**: Turret attack heavy vehicle, Turret attack heavy vehicule hero, **(0)**: Turret attack flying infantry, Turret attack flying vehicle
  * Turret attack pass through shield: No
  * Turret attack salvos: 1

## Internal stats

These stats internal to the system link different parts of data together.

  * Sub type: mortar_turret
  * Turret projectile type: projectileEmpireMortar

|Level    |1              |2              |3              |4              |5              |6              |7              |8              |9              |10              |
|---------|---------------|---------------|---------------|---------------|---------------|---------------|---------------|---------------|---------------|----------------|
|Turret id|t_empireMortar1|t_empireMortar2|t_empireMortar3|t_empireMortar4|t_empireMortar5|t_empireMortar6|t_empireMortar7|t_empireMortar8|t_empireMortar9|t_empireMortar10|


## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Asset name: mortarturret_tkn-mod
  * Bundle name: mortarturret_tkn-mod
  * Collect notify: 0
  * Cycle time: 0s
  * Destruct FX: fx_debris_{0}x{1}
  * Icon camera position: -23.91,25.41,24.96
  * Icon lookat position: 0.34,1.59,-0.27
  * Stash order: 1000
  * Store tab: not_in_store
  * Turret animation delay: 0
  * Turret attack S transition: 100
  * Turret attack arcs: Yes
  * Turret attack bullet: fx_mortar_projectile_r_sm
  * Turret attack hit spark: fx_mortar_hit_r_sm
  * Turret attack max scale: 100
  * Turret attack muzzle flash: fx_mortar_muzzle_r_sm
  * Turret attack name: Empire Mortar Turret
  * Turret attack spin speed: 2
  * Turret favorite target type: infantry
  * Turret gun position: "locator_gun":1
  * Turret max scale: 2

|Level                             |1                                                                                                          |2                                                                                                          |3                                                                                                          |4                                                                                                          |5                                                                                                          |6                                                                                                          |7                                                                                                          |8                                                                                                          |9                                                                                                          |10                                                                                                         |
|----------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
|Audio attack                      |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":50                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":51                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":52                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":53                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":54                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":55                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":56                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":57                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":58                                              |"sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":59                                              |
|Audio death                       |"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":25|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":26|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":27|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":28|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":29|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":30|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":31|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":32|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":33|"sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":34|
|Turret displayed damage per second|350                                                                                                        |525                                                                                                        |630                                                                                                        |840                                                                                                        |1015                                                                                                       |1120                                                                                                       |1225                                                                                                       |1330                                                                                                       |1435                                                                                                       |1575                                                                                                       |
|Turret tracker name               |mortarMesh_up1/barrelbaseMesh_up1                                                                          |mortarMesh_up2/barrelbaseMesh_up2                                                                          |mortarMesh_up3/barrelbaseMesh_up3                                                                          |mortarMesh_up4/barrelbaseMesh_up4                                                                          |mortarMesh_up5/barrelbaseMesh_up5                                                                          |mortarMesh_up6/barrelbaseMesh_up6                                                                          |mortarMesh_up7/barrelbaseMesh_up7                                                                          |mortarMesh_up8/barrelbaseMesh_up8                                                                          |mortarMesh_up9/barrelbaseMesh_up9                                                                          |mortarMesh_up10/barrelbaseMesh_up10                                                                        |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Turret arming delay: 0
  * Turret attack S1 time: 300ms
  * Turret attack S2 time: 300ms
  * Turret attack seeks target: No
  * Turret attack streams: no
  * Turret splash: false
  * Turret strict cool down: No
  * Turret timey wimey: 0.333333333333333314829616256247390992939472198486328125

|Level |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------|----|----|----|----|----|----|----|----|----|----|
|Max XP|10  |32  |66  |104 |160 |216 |294 |368 |468 |560 |
|Order |1263|1264|1265|1266|1267|1268|1269|1270|1271|1272|
|Xp    |5   |8   |11  |13  |16  |18  |21  |23  |26  |28  |

