---
title: Mortar Turret (empireMortar)
category: building
---

# Mortar Turret (empireMortar)

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
|Building     |[Headquarters 3](empireHQ.html)|[Headquarters 3](empireHQ.html)|[Headquarters 3](empireHQ.html)|[Headquarters 4](empireHQ.html)|[Headquarters 5](empireHQ.html)|[Headquarters 6](empireHQ.html)|[Headquarters 7](empireHQ.html)|[Headquarters 8](empireHQ.html)|[Headquarters 9](empireHQ.html)|[Headquarters 10](empireHQ.html)|


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
  * Turret target preferences: **Turret droideka (60)**, **Turret headquarters (60)**, **Turret heavy infantry (60)**, **Turret heavy vehicle (60)**, **Turret infantry (60)**, **Turret light vehicle (60)**, **Turret other building (60)**, **Turret ressource generator (60)**, **Turret storage (60)**, **Turret support troop (60)**, **Turret turret (60)**, Turret heavy infantry hero (1), Turret heavy vehicule hero (1), Turret infantry hero (1), Turret vehicule hero (1), Turret wall (1), Turret flying infantry (0), Turret flying vehicle (0)
  * Turret view range: 10

### Shooting

  * Turret animation delay: 0
  * Turret charge time: 1.650s
  * Turret clip retargeting: No
  * Turret gun shooting sequence: 1
  * Turret impact delay: 1s
  * Turret can shoot over walls: Yes
  * Turret reload time: 1.500s
  * Turret shot count: 1
  * Turret shot delay: 1ms

|Level                 |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------|----|----|----|----|----|----|----|----|----|----|
|Turret damage per shot|1155|1733|2079|2772|3350|3696|4043|4389|4736|5198|


  * Turret attack splash damage percentages: 100,30,20,10,10

|Level                                     |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------------------------------------------|----|----|----|----|----|----|----|----|----|----|
|Turret displayed damage per second        |350 |525 |630 |840 |1015|1120|1225|1330|1435|1575|
|Turret attack calculated damage per second|366 |549 |659 |879 |1063|1172|1283|1392|1503|1649|
|Turret attack calculated damage per clip  |1155|1733|2079|2772|3350|3696|4043|4389|4736|5198|


  * Turret attack cannons per sequence: 1
  * Turret attack cliptime: 3.151s
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

  * Audio attack: "sfx_attack_mortarlaunch_1":50,"sfx_attack_mortarlaunch_2":50
  * Audio death: "sfx_explosion_metal_1":25,"sfx_explosion_metal_2":25,"sfx_explosion_metal_3":25,"sfx_explosion_metal_4":25
  * Audio impact: "sfx_explosion_impact_1":50,"sfx_explosion_impact_2":50
  * Audio placement: "sfx_placement_turret_1":100
  * Collect notify: 0
  * Cycle time: 0s
  * Destruct FX: fx_debris_{0}x{1}
  * Stash order: 80
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

|Level                             |1                                |2                                |3                                |4                                |5                                |6                                |7                                |8                                |9                                |10                                 |
|----------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|---------------------------------|-----------------------------------|
|Asset name                        |mortarturret_emp-mod-up1         |mortarturret_emp-mod-up2         |mortarturret_emp-mod-up3         |mortarturret_emp-mod-up4         |mortarturret_emp-mod-up5         |mortarturret_emp-mod-up6         |mortarturret_emp-mod-up7         |mortarturret_emp-mod-up8         |mortarturret_emp-mod-up9         |mortarturret_emp-mod-up10          |
|Buff asset offset                 |-1,3,-1                          |-1,3,-1                          |-1,3,-1                          |-1,3,-1                          |-1.6,1.6,-1.6                    |-1.4,1.6,-1.4                    |-1.2,2,-1.2                      |-1.2,2,-1.2                      |-1.2,2,-1.2                      |-1.2,2,-1.2                        |
|Bundle name                       |mortarturret_emp-mod-up1         |mortarturret_emp-mod-up2         |mortarturret_emp-mod-up3         |mortarturret_emp-mod-up4         |mortarturret_emp-mod-up5         |mortarturret_emp-mod-up6         |mortarturret_emp-mod-up7         |mortarturret_emp-mod-up8         |mortarturret_emp-mod-up9         |mortarturret_emp-mod-up10          |
|Icon camera position              |-23.91,25.41,24.96               |-23.91,25.41,24.96               |-23.91,25.41,24.96               |-23.91,25.41,24.96               |-23.91,25.41,24.96               |-23.91,25.41,24.96               |-23.91,25.41,24.96               |-23.91,25.41,24.96               |-25.64,30.71,29.55               |-25.64,30.71,29.55                 |
|Icon lookat position              |0.34,1.59,-0.27                  |0.34,1.59,-0.27                  |0.34,1.59,-0.27                  |0.34,1.59,-0.27                  |0.34,1.59,-0.27                  |0.34,1.59,-0.27                  |0.34,1.59,-0.27                  |0.34,1.59,-0.27                  |0.41,2.03,-0.59                  |0.41,2.03,-0.59                    |
|Store tab                         |decorations                      |(not found)                      |(not found)                      |(not found)                      |(not found)                      |(not found)                      |(not found)                      |(not found)                      |(not found)                      |(not found)                        |
|Turret displayed damage per second|350                              |525                              |630                              |840                              |1015                             |1120                             |1225                             |1330                             |1435                             |1575                               |
|Turret tracker name               |mortarMesh_up1/barrelbaseMesh_up1|mortarMesh_up2/barrelbaseMesh_up2|mortarMesh_up3/barrelbaseMesh_up3|mortarMesh_up4/barrelbaseMesh_up4|mortarMesh_up5/barrelbaseMesh_up5|mortarMesh_up6/barrelbaseMesh_up6|mortarMesh_up7/barrelbaseMesh_up7|mortarMesh_up8/barrelbaseMesh_up8|mortarMesh_up9/barrelbaseMesh_up9|mortarMesh_up10/barrelbaseMesh_up10|


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Order: 21
  * Turret arming delay: 0
  * Turret attack S1 time: 300ms
  * Turret attack S2 time: 300ms
  * Turret attack seeks target: No
  * Turret attack streams: no
  * Turret splash: false
  * Turret strict cool down: No
  * Turret timey wimey: 0.333333333333333314829616256247390992939472198486328125

|Level |1 |2  |3  |4  |5  |6  |7  |8  |9   |10  |
|------|--|---|---|---|---|---|---|---|----|----|
|Max XP|50|120|210|320|450|600|770|960|1170|1400|
|Xp    |25|30 |35 |40 |45 |50 |55 |60 |65  |70  |


