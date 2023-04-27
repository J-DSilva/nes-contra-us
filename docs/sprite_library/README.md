This folder contains every sprite that can be loaded in Contra.  The sprites
here are not used by the game code, they were extracted from the ROM for ease of
viewing.

The name of each sprite is the same as the label in bank1.asm in the 2 large
sprite tables sprite_ptr_tbl_0 and sprite_ptr_tbl_1.

The player lives medals in the heads up display (HUD) are not in the sprite
tables, but the tiles are written directly to the OAMDMA via the CPU buffer.

# Sprite Table
|   | 0                                                                                                          | 1                                                                                                          | 2                                                                                                          | 3                                                                                                          | 4                                                                                                          | 5                                                                                                          | 6                                                                                                          | 7                                                                                                          | 8                                                                                                          | 9                                                                                                          | a                                                                                                          | b                                                                                                          | c                                                                                                          | d                                                                                                          | e                                                                                                          | f                                                                                                          |
|---|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 0 |                                                                                                            |                                                                                                            | ![sprite_02](sprite_02.png?raw=true "sprite_02") ![sprite_02_p2](sprite_02_p2.png?raw=true "sprite_02_p2") | ![sprite_03](sprite_03.png?raw=true "sprite_03") ![sprite_03_p2](sprite_03_p2.png?raw=true "sprite_03_p2") | ![sprite_04](sprite_04.png?raw=true "sprite_04") ![sprite_04_p2](sprite_04_p2.png?raw=true "sprite_04_p2") | ![sprite_05](sprite_05.png?raw=true "sprite_05") ![sprite_05_p2](sprite_05_p2.png?raw=true "sprite_05_p2") | ![sprite_06](sprite_06.png?raw=true "sprite_06") ![sprite_06_p2](sprite_06_p2.png?raw=true "sprite_06_p2") | ![sprite_07](sprite_07.png?raw=true "sprite_07")                                                           | ![sprite_08](sprite_08.png?raw=true "sprite_08") ![sprite_08_p2](sprite_08_p2.png?raw=true "sprite_08_p2") | ![sprite_09](sprite_09.png?raw=true "sprite_09") ![sprite_09_p2](sprite_09_p2.png?raw=true "sprite_09_p2") | ![sprite_0a](sprite_0a.png?raw=true "sprite_0a") ![sprite_0a_p2](sprite_0a_p2.png?raw=true "sprite_0a_p2") | ![sprite_0b](sprite_0b.png?raw=true "sprite_0b") ![sprite_0b_p2](sprite_0b_p2.png?raw=true "sprite_0b_p2") | ![sprite_0c](sprite_0c.png?raw=true "sprite_0c") ![sprite_0c_p2](sprite_0c_p2.png?raw=true "sprite_0c_p2") | ![sprite_0d](sprite_0d.png?raw=true "sprite_0d") ![sprite_0d_p2](sprite_0d_p2.png?raw=true "sprite_0d_p2") | ![sprite_0e](sprite_0e.png?raw=true "sprite_0e") ![sprite_0e_p2](sprite_0e_p2.png?raw=true "sprite_0e_p2") | ![sprite_0f](sprite_0f.png?raw=true "sprite_0f") ![sprite_0f_p2](sprite_0f_p2.png?raw=true "sprite_0f_p2") |
| 1 | ![sprite_10](sprite_10.png?raw=true "sprite_10") ![sprite_10_p2](sprite_10_p2.png?raw=true "sprite_10_p2") | ![sprite_11](sprite_11.png?raw=true "sprite_11") ![sprite_11_p2](sprite_11_p2.png?raw=true "sprite_11_p2") | ![sprite_12](sprite_12.png?raw=true "sprite_12") ![sprite_12_p2](sprite_12_p2.png?raw=true "sprite_12_p2") | ![sprite_13](sprite_13.png?raw=true "sprite_13") ![sprite_13_p2](sprite_13_p2.png?raw=true "sprite_13_p2") | ![sprite_14](sprite_14.png?raw=true "sprite_14") ![sprite_14_p2](sprite_14_p2.png?raw=true "sprite_14_p2") | ![sprite_15](sprite_15.png?raw=true "sprite_15") ![sprite_15_p2](sprite_15_p2.png?raw=true "sprite_15_p2") | ![sprite_16](sprite_16.png?raw=true "sprite_16") ![sprite_16_p2](sprite_16_p2.png?raw=true "sprite_16_p2") | ![sprite_17](sprite_17.png?raw=true "sprite_17") ![sprite_17_p2](sprite_17_p2.png?raw=true "sprite_17_p2") | ![sprite_18](sprite_18.png?raw=true "sprite_18")                                                           | ![sprite_19](sprite_19.png?raw=true "sprite_19")                                                           | ![sprite_1a](sprite_1a.png?raw=true "sprite_1a")                                                           | ![sprite_1b](sprite_1b.png?raw=true "sprite_1b")                                                           | ![sprite_1c](sprite_1c.png?raw=true "sprite_1c")                                                           | ![sprite_1d](sprite_1d.png?raw=true "sprite_1d")                                                           | ![sprite_1e](sprite_1e.png?raw=true "sprite_1e")                                                           | ![sprite_1f](sprite_1f.png?raw=true "sprite_1f")                                                           |
| 2 | ![sprite_20](sprite_20.png?raw=true "sprite_20")                                                           | ![sprite_21](sprite_21.png?raw=true "sprite_21")                                                           | ![sprite_22](sprite_22.png?raw=true "sprite_22")                                                           | ![sprite_23](sprite_23.png?raw=true "sprite_23")                                                           | ![sprite_24](sprite_24.png?raw=true "sprite_24")                                                           | ![sprite_25](sprite_25.png?raw=true "sprite_25")                                                           | ![sprite_26](sprite_26.png?raw=true "sprite_26")                                                           | ![sprite_27](sprite_27.png?raw=true "sprite_27")                                                           | ![sprite_28](sprite_28.png?raw=true "sprite_28")                                                           | ![sprite_29](sprite_29.png?raw=true "sprite_29")                                                           | ![sprite_2a](sprite_2a.png?raw=true "sprite_2a")                                                           | ![sprite_2b](sprite_2b.png?raw=true "sprite_2b")                                                           | ![sprite_2c](sprite_2c.png?raw=true "sprite_2c")                                                           | ![sprite_2d](sprite_2d.png?raw=true "sprite_2d")                                                           |                                                                                                            | ![sprite_2f](sprite_2f.png?raw=true "sprite_2f")                                                           |
| 3 | ![sprite_30](sprite_30.png?raw=true "sprite_30")                                                           | ![sprite_31](sprite_31.png?raw=true "sprite_31")                                                           | ![sprite_32](sprite_32.png?raw=true "sprite_32")                                                           | ![sprite_33](sprite_33.png?raw=true "sprite_33")                                                           | ![sprite_34](sprite_34.png?raw=true "sprite_34")                                                           | ![sprite_35](sprite_35.png?raw=true "sprite_35")                                                           | ![sprite_36](sprite_36.png?raw=true "sprite_36")                                                           | ![sprite_37](sprite_37.png?raw=true "sprite_37")                                                           | ![sprite_38](sprite_38.png?raw=true "sprite_38")                                                           | ![sprite_39](sprite_39.png?raw=true "sprite_39")                                                           | ![sprite_3a](sprite_3a.png?raw=true "sprite_3a")                                                           | ![sprite_3b](sprite_3b.png?raw=true "sprite_3b")                                                           | ![sprite_3c](sprite_3c.png?raw=true "sprite_3c")                                                           | ![sprite_3d](sprite_3d.png?raw=true "sprite_3d")                                                           | ![sprite_3e](sprite_3e.png?raw=true "sprite_3e")                                                           | ![sprite_3f](sprite_3f.png?raw=true "sprite_3f")                                                           |
| 4 | ![sprite_40](sprite_40.png?raw=true "sprite_40")                                                           | ![sprite_41](sprite_41.png?raw=true "sprite_41")                                                           | ![sprite_42](sprite_42.png?raw=true "sprite_42")                                                           | ![sprite_43](sprite_43.png?raw=true "sprite_43")                                                           | ![sprite_44](sprite_44.png?raw=true "sprite_44")                                                           | ![sprite_45](sprite_45.png?raw=true "sprite_45")                                                           | ![sprite_46](sprite_46.png?raw=true "sprite_46")                                                           | ![sprite_47](sprite_47.png?raw=true "sprite_47")                                                           | ![sprite_48](sprite_48.png?raw=true "sprite_48")                                                           | ![sprite_49](sprite_49.png?raw=true "sprite_49")                                                           | ![sprite_4a](sprite_4a.png?raw=true "sprite_4a")                                                           | ![sprite_4b](sprite_4b.png?raw=true "sprite_4b")                                                           | ![sprite_4c](sprite_4c.png?raw=true "sprite_4c")                                                           | ![sprite_4d](sprite_4d.png?raw=true "sprite_4d")                                                           | ![sprite_4e](sprite_4e.gif?raw=true "sprite_4e")                                                           |                                                                                                            |
| 5 | ![sprite_50](sprite_50.png?raw=true "sprite_50") ![sprite_50_p2](sprite_50_p2.png?raw=true "sprite_50_p2") | ![sprite_51](sprite_51.png?raw=true "sprite_51") ![sprite_51_p2](sprite_51_p2.png?raw=true "sprite_51_p2") | ![sprite_52](sprite_52.png?raw=true "sprite_52") ![sprite_52_p2](sprite_52_p2.png?raw=true "sprite_52_p2") | ![sprite_53](sprite_53.png?raw=true "sprite_53") ![sprite_53_p2](sprite_53_p2.png?raw=true "sprite_53_p2") | ![sprite_54](sprite_54.png?raw=true "sprite_54") ![sprite_54_p2](sprite_54_p2.png?raw=true "sprite_54_p2") | ![sprite_55](sprite_55.png?raw=true "sprite_55") ![sprite_55_p2](sprite_55_p2.png?raw=true "sprite_55_p2") | ![sprite_56](sprite_56.png?raw=true "sprite_56") ![sprite_56_p2](sprite_56_p2.png?raw=true "sprite_56_p2") | ![sprite_57](sprite_57.png?raw=true "sprite_57") ![sprite_57_p2](sprite_57_p2.png?raw=true "sprite_57_p2") | ![sprite_58](sprite_58.png?raw=true "sprite_58") ![sprite_58_p2](sprite_58_p2.png?raw=true "sprite_58_p2") |                                                                                                            |                                                                                                            |                                                                                                            |                                                                                                            | ![sprite_5d](sprite_5d.png?raw=true "sprite_5d")                                                           | ![sprite_5e](sprite_5e.png?raw=true "sprite_5e")                                                           | ![sprite_5f](sprite_5f.png?raw=true "sprite_5f")                                                           |
| 6 | ![sprite_60](sprite_60.png?raw=true "sprite_60")                                                           | ![sprite_61](sprite_61.png?raw=true "sprite_61")                                                           | ![sprite_62](sprite_62.png?raw=true "sprite_62")                                                           | ![sprite_63](sprite_63.png?raw=true "sprite_63")                                                           | ![sprite_64](sprite_64.png?raw=true "sprite_64")                                                           |                                                                                                            |                                                                                                            |                                                                                                            | ![sprite_68](sprite_68.png?raw=true "sprite_68")                                                           | ![sprite_69](sprite_69.png?raw=true "sprite_69")                                                           | ![sprite_6a](sprite_6a.png?raw=true "sprite_6a")                                                           | ![sprite_6b](sprite_6b.png?raw=true "sprite_6b")                                                           | ![sprite_6c](sprite_6c.png?raw=true "sprite_6c")                                                           | ![sprite_6d](sprite_6d.png?raw=true "sprite_6d")                                                           | ![sprite_6e](sprite_6e.png?raw=true "sprite_6e")                                                           | ![sprite_6f](sprite_6f.png?raw=true "sprite_6f")                                                           |
| 7 | ![sprite_70](sprite_70.png?raw=true "sprite_70")                                                           | ![sprite_71](sprite_71.png?raw=true "sprite_71")                                                           | ![sprite_72](sprite_72.png?raw=true "sprite_72")                                                           | ![sprite_73](sprite_73.png?raw=true "sprite_73")                                                           | ![sprite_74](sprite_74.png?raw=true "sprite_74")                                                           | ![sprite_75](sprite_75.png?raw=true "sprite_75")                                                           | ![sprite_76](sprite_76.png?raw=true "sprite_76")                                                           | ![sprite_77](sprite_77.png?raw=true "sprite_77")                                                           | ![sprite_78](sprite_78.png?raw=true "sprite_78")                                                           | ![sprite_79](sprite_79.png?raw=true "sprite_79")                                                           | ![sprite_7a](sprite_7a.png?raw=true "sprite_7a")                                                           | ![sprite_7b](sprite_7b.png?raw=true "sprite_7b")                                                           | ![sprite_7c](sprite_7c.png?raw=true "sprite_7c")                                                           | ![sprite_7d](sprite_7d.png?raw=true "sprite_7d")                                                           | ![sprite_7e](sprite_7e.png?raw=true "sprite_7e")                                                           |                                                                                                            |
| 8 |                                                                                                            |                                                                                                            | ![sprite_82](sprite_82.png?raw=true "sprite_82")                                                           | ![sprite_83](sprite_83.png?raw=true "sprite_83")                                                           | ![sprite_84](sprite_84.png?raw=true "sprite_84")                                                           | ![sprite_85](sprite_85.png?raw=true "sprite_85")                                                           | ![sprite_86](sprite_86.png?raw=true "sprite_86")                                                           | ![sprite_87](sprite_87.png?raw=true "sprite_87")                                                           | ![sprite_88](sprite_88.png?raw=true "sprite_88")                                                           | ![sprite_89](sprite_89.png?raw=true "sprite_89")                                                           | ![sprite_8a](sprite_8a.png?raw=true "sprite_8a")                                                           | ![sprite_8b](sprite_8b.png?raw=true "sprite_8b")                                                           | ![sprite_8c](sprite_8c.png?raw=true "sprite_8c")                                                           | ![sprite_8d](sprite_8d.png?raw=true "sprite_8d")                                                           | ![sprite_8e](sprite_8e.png?raw=true "sprite_8e")                                                           | ![sprite_8f](sprite_8f.png?raw=true "sprite_8f")                                                           |
| 9 | ![sprite_90](sprite_90.png?raw=true "sprite_90")                                                           | ![sprite_91](sprite_91.png?raw=true "sprite_91") ![sprite_91_p2](sprite_91_p2.png?raw=true "sprite_91_p2") | ![sprite_92](sprite_92.png?raw=true "sprite_92")                                                           | ![sprite_93](sprite_93.png?raw=true "sprite_93")                                                           | ![sprite_94](sprite_94.png?raw=true "sprite_94")                                                           | ![sprite_95](sprite_95.png?raw=true "sprite_95")                                                           | ![sprite_96](sprite_96.png?raw=true "sprite_96")                                                           | ![sprite_97](sprite_97.png?raw=true "sprite_97")                                                           | ![sprite_98](sprite_98.png?raw=true "sprite_98")                                                           | ![sprite_99](sprite_99.png?raw=true "sprite_99")                                                           | ![sprite_9a](sprite_9a.png?raw=true "sprite_9a")                                                           | ![sprite_9b](sprite_9b.png?raw=true "sprite_9b")                                                           | ![sprite_9c](sprite_9c.png?raw=true "sprite_9c")                                                           | ![sprite_9d](sprite_9d.png?raw=true "sprite_9d")                                                           | ![sprite_9e](sprite_9e.png?raw=true "sprite_9e")                                                           | ![sprite_9f](sprite_9f.png?raw=true "sprite_9f")                                                           |
| a | ![sprite_a0](sprite_a0.png?raw=true "sprite_a0")                                                           | ![sprite_a1](sprite_a1.png?raw=true "sprite_a1")                                                           | ![sprite_a2](sprite_a2.png?raw=true "sprite_a2")                                                           | ![sprite_a3](sprite_a3.png?raw=true "sprite_a3")                                                           | ![sprite_a4](sprite_a4.png?raw=true "sprite_a4")                                                           | ![sprite_a5](sprite_a5.png?raw=true "sprite_a5")                                                           | ![sprite_a6](sprite_a6.png?raw=true "sprite_a6")                                                           | ![sprite_a7](sprite_a7.png?raw=true "sprite_a7")                                                           | ![sprite_a8](sprite_a8.png?raw=true "sprite_a8")                                                           | ![sprite_a9](sprite_a9.png?raw=true "sprite_a9")                                                           | ![sprite_aa](sprite_aa.png?raw=true "sprite_aa")                                                           | ![sprite_ab](sprite_ab.png?raw=true "sprite_ab")                                                           | ![sprite_ac](sprite_ac.png?raw=true "sprite_ac")                                                           | ![sprite_ad](sprite_ad.png?raw=true "sprite_ad")                                                           | ![sprite_ae](sprite_ae.png?raw=true "sprite_ae")                                                           | ![sprite_af](sprite_af.png?raw=true "sprite_af")                                                           |
| b | ![sprite_b0](sprite_b0.png?raw=true "sprite_b0")                                                           | ![sprite_b1](sprite_b1.png?raw=true "sprite_b1")                                                           | ![sprite_b2](sprite_b2.png?raw=true "sprite_b2")                                                           | ![sprite_b3](sprite_b3.png?raw=true "sprite_b3")                                                           | ![sprite_b4](sprite_b4.png?raw=true "sprite_b4")                                                           | ![sprite_b5](sprite_b5.png?raw=true "sprite_b5")                                                           | ![sprite_b6](sprite_b6.png?raw=true "sprite_b6")                                                           | ![sprite_b7](sprite_b7.png?raw=true "sprite_b7")                                                           | ![sprite_b8](sprite_b8.png?raw=true "sprite_b8")                                                           | ![sprite_b9](sprite_b9.png?raw=true "sprite_b9")                                                           | ![sprite_ba](sprite_ba.png?raw=true "sprite_ba")                                                           | ![sprite_bb](sprite_bb.png?raw=true "sprite_bb")                                                           | ![sprite_bc](sprite_bc.png?raw=true "sprite_bc")                                                           | ![sprite_bd](sprite_bd.png?raw=true "sprite_bd")                                                           | ![sprite_be](sprite_be.png?raw=true "sprite_be")                                                           | ![sprite_bf](sprite_bf.png?raw=true "sprite_bf")                                                           |
| c | ![sprite_c0](sprite_c0.png?raw=true "sprite_c0")                                                           | ![sprite_c1](sprite_c1.png?raw=true "sprite_c1")                                                           | ![sprite_c2](sprite_c2.png?raw=true "sprite_c2")                                                           | ![sprite_c3](sprite_c3.png?raw=true "sprite_c3")                                                           | ![sprite_c4](sprite_c4.png?raw=true "sprite_c4")                                                           | ![sprite_c5](sprite_c5.png?raw=true "sprite_c5")                                                           | ![sprite_c6](sprite_c6.png?raw=true "sprite_c6")                                                           | ![sprite_c7](sprite_c7.png?raw=true "sprite_c7")                                                           | ![sprite_c8](sprite_c8.png?raw=true "sprite_c8")                                                           | ![sprite_c9](sprite_c9.png?raw=true "sprite_c9")                                                           | ![sprite_ca](sprite_ca.png?raw=true "sprite_ca")                                                           | ![sprite_cb](sprite_cb.png?raw=true "sprite_cb")                                                           | ![sprite_cc](sprite_cc.png?raw=true "sprite_cc")                                                           | ![sprite_cd](sprite_cd.png?raw=true "sprite_cd")                                                           | ![sprite_ce](sprite_ce.png?raw=true "sprite_ce")                                                           | ![sprite_cf](sprite_cf.png?raw=true "sprite_cf")                                                           |

# Hud Sprites

* Player 1
  * ![player_1_lives_medal](player_1_lives_medal.png?raw=true "player_1_lives_medal")
  * ![player_1_game_over](player_1_game_over.png?raw=true "player_1_game_over")
* Player 2
  * ![player_2_lives_medal](player_2_lives_medal.png?raw=true "player_2_lives_medal")
  * ![player_2_game_over](player_2_game_over.png?raw=true "player_2_game_over")

# Sprites Not Used In Game

* ![sprite_78](sprite_78.png?raw=true "sprite_78") (`sprite_78`) exists in the
  game code, but isn't used.  It is identical to `sprite_74` and that is what is
  used insead.
* `sprite_59`, `sprite_5a`, `sprite_5b`, `sprite_5c`, `sprite_65`, `sprite_66`,
  and `sprite_67` are all empty and not used in the game.
* `sprite_80` and `sprite_81` are defined in the game, but never used so I can't
  tell which pattern tiles they are supposed to utilize.