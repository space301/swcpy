---
title: Rocket Turret (empireRocketTurret)
category: building
---

# Rocket Turret (empireRocketTurret)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: turret
  * Cross credits: 0
  * Side: Empire
  * Force reticle when targeted: No
  * Hide if locked: No
  * Produce: 0
  * Type: turret

|Level          |1   |2   |3    |4    |5    |6    |7    |8     |9     |10    |
|---------------|----|----|-----|-----|-----|-----|-----|------|------|------|
|Cross materials|450 |900 |4500 |13500|27000|72000|90000|135000|360000|540000|
|Cross time     |10m |12m |1h12m|4h48m|8h   |14h  |20h  |1d4h  |1d12h |2d    |
|Health         |5000|7500|9000 |12000|14500|16000|17500|22000 |24500 |27000 |
|Max quantity   |2   |4   |6    |8    |10   |12   |14   |16    |18    |20    |
|Time           |1m  |30m |4h   |16h  |1d12h|2d12h|4d   |6d    |1w1d  |1w3d  |


### Training stats

|Level        |1                              |2                              |3                              |4                              |5                              |6                              |7                              |8                              |9                              |10                              |
|-------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|-------------------------------|--------------------------------|
|Training cost|1500 All.                      |3000 All.                      |20000 All.                     |55000 All.                     |100000 All.                    |250000 All.                    |500000 All.                    |1000000 All.                   |3000000 All.                   |5000000 All.                    |
|Building     |[Headquarters 4](empireHQ.html)|[Headquarters 4](empireHQ.html)|[Headquarters 4](empireHQ.html)|[Headquarters 4](empireHQ.html)|[Headquarters 5](empireHQ.html)|[Headquarters 6](empireHQ.html)|[Headquarters 7](empireHQ.html)|[Headquarters 8](empireHQ.html)|[Headquarters 9](empireHQ.html)|[Headquarters 10](empireHQ.html)|


### Upgrading stats

  * Upgrade requirements: Nothing

### Movement stats

  * Acceleration: 0
  * Max speed: 0
  * Unit size on map: 2x2

## Turret attack : Rocket Turret Empire


### Targeting

  * Turret max attack range: 10
  * Turret min attack range: 0
  * Turret target preference strength: 90
  * Turret target preferences: **Turret flying vehicle (100)**, **Turret heavy vehicle (100)**, **Turret light vehicle (100)**, **Turret turret (100)**, Turret droideka (50), Turret flying infantry (50), Turret heavy infantry (50), Turret infantry (50), Turret support troop (50), Turret other building (25), Turret headquarters (1), Turret heavy infantry hero (1), Turret heavy vehicule hero (1), Turret infantry hero (1), Turret vehicule hero (1), Turret ressource generator (0), Turret storage (0), Turret wall (0)
  * Turret view range: 10

### Shooting

  * Turret animation delay: 0
  * Turret charge time: 1.750s
  * Turret clip retargeting: No
  * Turret gun shooting sequence: 1,1
  * Turret impact delay: 250ms
  * Turret can shoot over walls: Yes
  * Turret reload time: 1.050s
  * Turret shot count: 6
  * Turret shot delay: 175ms

|Level                 |1  |2  |3  |4  |5  |6  |7   |8   |9   |10  |
|----------------------|---|---|---|---|---|---|----|----|----|----|
|Turret damage per shot|306|459|551|735|888|980|1072|1164|1256|1378|


  * Turret attack splash damage percentages: 100

|Level                                     |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------------------------------------------|----|----|----|----|----|----|----|----|----|----|
|Turret displayed damage per second        |500 |750 |900 |1200|1450|1600|1750|1900|2050|2250|
|Turret attack calculated damage per second|552 |828 |994 |1326|1602|1768|1934|2100|2266|2486|
|Turret attack calculated damage per clip  |1836|2754|3306|4410|5328|5880|6432|6984|7536|8268|


  * Turret attack cannons per sequence: 2
  * Turret attack cliptime: 3.325s
  * Turret attack directional: Yes
  * Turret attack is deflectable: No
  * Turret attack max speed: 12
  * Turret attack damage multipliers: **(200)**: Turret attack flying vehicle, Turret attack light vehicle, Turret attack vehicule hero, **(150)**: Turret attack heavy vehicle, Turret attack heavy vehicule hero, **(100)**: Turret attack droideka, Turret attack headquarters, Turret attack other building, Turret attack ressource generator, Turret attack shield, Turret attack shield generator, Turret attack storage, Turret attack trap, Turret attack turret, Turret attack wall, **(50)**: Turret attack flying infantry, Turret attack infantry, Turret attack infantry hero, Turret attack support troop, **(25)**: Turret attack heavy infantry, Turret attack heavy infantry hero
  * Turret attack pass through shield: No
  * Turret attack salvos: 3

## Internal stats

These stats internal to the system link different parts of data together.

  * Sub type: rocket_turret
  * Turret projectile type: projectileRocketTurretEmpire

|Level    |1                    |2                    |3                    |4                    |5                    |6                    |7                    |8                    |9                    |10                    |
|---------|---------------------|---------------------|---------------------|---------------------|---------------------|---------------------|---------------------|---------------------|---------------------|----------------------|
|Turret id|t_empireRocketTurret1|t_empireRocketTurret2|t_empireRocketTurret3|t_empireRocketTurret4|t_empireRocketTurret5|t_empireRocketTurret6|t_empireRocketTurret7|t_empireRocketTurret8|t_empireRocketTurret9|t_empireRocketTurret10|


## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Audio attack: "sfx_attack_rocket_1":20,"sfx_attack_rocket_2":20,"sfx_attack_rocket_3":20,"sfx_attack_rocket_4":20,"sfx_attack_rocket_5":20
  * Audio death: "sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":25
  * Audio impact: "sfx_explosion_impact_1":50,"sfx_explosion_impact_2":50
  * Audio placement: "sfx_placement_turret_1":100
  * Collect notify: 0
  * Cycle time: 0s
  * Destruct FX: fx_debris_{0}x{1}
  * Stash order: 70
  * Turret attack arcs: No
  * Turret attack bullet: fx_rocket_projectile_r_med
  * Turret attack hit spark: fx_rocket_hit_r_med
  * Turret attack max scale: 100
  * Turret attack muzzle flash: fx_rocket_muzzle_r_med
  * Turret attack name: Rocket Turret Empire
  * Turret attack spin speed: 0
  * Turret favorite target type: lightVehicle
  * Turret max scale: 0

|Level                             |1                                                                                                                                                            |2                                                                                                                                                            |3                                                                                                                                                            |4                                                                                                                                                            |5                                                                                                                                                            |6                                                                                                                                                            |7                                                                                                                                                            |8                                                                                                                                                            |9                                                                                                                                                            |10                                                                                                                                                                   |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Asset name                        |rocketturret_emp-mod-up1                                                                                                                                     |rocketturret_emp-mod-up2                                                                                                                                     |rocketturret_emp-mod-up3                                                                                                                                     |rocketturret_emp-mod-up4                                                                                                                                     |rocketturret_emp-mod-up5                                                                                                                                     |rocketturret_emp-mod-up6                                                                                                                                     |rocketturret_emp-mod-up7                                                                                                                                     |rocketturret_emp-mod-up8                                                                                                                                     |rocketturret_emp-mod-up9                                                                                                                                     |rocketturret_emp-mod-up10                                                                                                                                            |
|Buff asset offset                 |-1,3,-1                                                                                                                                                      |-1,3,-1                                                                                                                                                      |-1,3,-1                                                                                                                                                      |-1,3,-1                                                                                                                                                      |-1,3.2,-1                                                                                                                                                    |-1,3.2,-1                                                                                                                                                    |-1,3.4,-1                                                                                                                                                    |-1,3.4,-1                                                                                                                                                    |-1,3.4,-1                                                                                                                                                    |-1,3.4,-1                                                                                                                                                            |
|Bundle name                       |rocketturret_emp-mod-up1                                                                                                                                     |rocketturret_emp-mod-up2                                                                                                                                     |rocketturret_emp-mod-up3                                                                                                                                     |rocketturret_emp-mod-up4                                                                                                                                     |rocketturret_emp-mod-up5                                                                                                                                     |rocketturret_emp-mod-up6                                                                                                                                     |rocketturret_emp-mod-up7                                                                                                                                     |rocketturret_emp-mod-up8                                                                                                                                     |rocketturret_emp-mod-up9                                                                                                                                     |rocketturret_emp-mod-up10                                                                                                                                            |
|Icon camera position              |-23.91,25.41,24.96                                                                                                                                           |-23.91,25.41,24.96                                                                                                                                           |-23.91,25.41,24.96                                                                                                                                           |-23.91,25.41,24.96                                                                                                                                           |-23.91,25.41,24.96                                                                                                                                           |-23.91,25.41,24.96                                                                                                                                           |-23.91,25.41,24.96                                                                                                                                           |-23.91,25.41,24.96                                                                                                                                           |-27.02,32.27,31.11                                                                                                                                           |-27.02,32.27,31.11                                                                                                                                                   |
|Icon lookat position              |0.34,1.59,-0.27                                                                                                                                              |0.34,1.59,-0.27                                                                                                                                              |0.34,1.59,-0.27                                                                                                                                              |0.34,1.59,-0.27                                                                                                                                              |0.34,1.59,-0.27                                                                                                                                              |0.34,1.59,-0.27                                                                                                                                              |0.34,1.59,-0.27                                                                                                                                              |0.34,1.59,-0.27                                                                                                                                              |0.41,2.03,-0.59                                                                                                                                              |0.41,2.03,-0.59                                                                                                                                                      |
|Store tab                         |decorations                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                  |(not found)                                                                                                                                                          |
|Turret displayed damage per second|500                                                                                                                                                          |750                                                                                                                                                          |900                                                                                                                                                          |1200                                                                                                                                                         |1450                                                                                                                                                         |1600                                                                                                                                                         |1750                                                                                                                                                         |1900                                                                                                                                                         |2050                                                                                                                                                         |2250                                                                                                                                                                 |
|Turret gun position               |"rotateMesh_up1/tiltBarMesh_up1/aimMesh_up1/turretHeadMesh_up1/locator_gun1":1,"rotateMesh_up1/tiltBarMesh_up1/aimMesh_up1/turretHeadMesh_up1/locator_gun2":1|"rotateMesh_up2/tiltBarMesh_up2/aimMesh_up2/turretHeadMesh_up2/locator_gun1":1,"rotateMesh_up2/tiltBarMesh_up2/aimMesh_up2/turretHeadMesh_up2/locator_gun2":1|"rotateMesh_up3/tiltBarMesh_up3/aimMesh_up3/turretHeadMesh_up3/locator_gun1":1,"rotateMesh_up3/tiltBarMesh_up3/aimMesh_up3/turretHeadMesh_up3/locator_gun2":1|"rotateMesh_up4/tiltBarMesh_up4/aimMesh_up4/turretHeadMesh_up4/locator_gun1":1,"rotateMesh_up4/tiltBarMesh_up4/aimMesh_up4/turretHeadMesh_up4/locator_gun2":1|"rotateMesh_up5/tiltBarMesh_up5/aimMesh_up5/turretHeadMesh_up5/locator_gun1":1,"rotateMesh_up5/tiltBarMesh_up5/aimMesh_up5/turretHeadMesh_up5/locator_gun2":1|"rotateMesh_up6/tiltBarMesh_up6/aimMesh_up6/turretHeadMesh_up6/locator_gun1":1,"rotateMesh_up6/tiltBarMesh_up6/aimMesh_up6/turretHeadMesh_up6/locator_gun2":1|"rotateMesh_up7/tiltBarMesh_up7/aimMesh_up7/turretHeadMesh_up7/locator_gun1":1,"rotateMesh_up7/tiltBarMesh_up7/aimMesh_up7/turretHeadMesh_up7/locator_gun2":1|"rotateMesh_up8/tiltBarMesh_up8/aimMesh_up8/turretHeadMesh_up8/locator_gun1":1,"rotateMesh_up8/tiltBarMesh_up8/aimMesh_up8/turretHeadMesh_up8/locator_gun2":1|"rotateMesh_up9/tiltBarMesh_up9/aimMesh_up9/turretHeadMesh_up9/locator_gun1":1,"rotateMesh_up9/tiltBarMesh_up9/aimMesh_up9/turretHeadMesh_up9/locator_gun2":1|"rotateMesh_up10/tiltBarMesh_up10/aimMesh_up10/turretHeadMesh_up10/locator_gun1":1,"rotateMesh_up10/tiltBarMesh_up10/aimMesh_up10/turretHeadMesh_up10/locator_gun2":1|
|Turret tracker name               |rotateMesh_up1                                                                                                                                               |rotateMesh_up2                                                                                                                                               |rotateMesh_up3                                                                                                                                               |rotateMesh_up4                                                                                                                                               |rotateMesh_up5                                                                                                                                               |rotateMesh_up6                                                                                                                                               |rotateMesh_up7                                                                                                                                               |rotateMesh_up8                                                                                                                                               |rotateMesh_up9                                                                                                                                               |rotateMesh_up10                                                                                                                                                      |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Order: 22
  * Turret arming delay: 0
  * Turret attack seeks target: Yes
  * Turret attack streams: no
  * Turret splash: false
  * Turret strict cool down: No
  * Turret timey wimey: 1.6326530612244898321705477428622543811798095703125

|Level |1 |2  |3  |4  |5  |6  |7  |8  |9   |10  |
|------|--|---|---|---|---|---|---|---|----|----|
|Max XP|50|120|210|320|450|600|770|960|1170|1400|
|Xp    |25|30 |35 |40 |45 |50 |55 |60 |65  |70  |


