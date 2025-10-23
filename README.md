## MySQLの設定
- **データベース名**： enemy_down
  - **テーブル名**： game_config｜player_score｜spawn_enemy
#### game_config
| id | game_time | difficulty |
| ---- | ---- | ---- |
| 1 | 20 | easy |
| 2 | 30 | normal |
| 3 | 40 | hard |

#### player_score
| id | player_name | score | difficulty | registered_at |
| ---- | ---- | ---- | ---- | ---- |
| 1 | masahiro | 193 | normal | 1993-01-21 |

#### spawn_enemy
| id | difficulty | enemy_name | score |
| ---- | ---- | ---- | ---- |
| 1 | eady | ZOMBIE | 10 |
| 2 | normal| SKELETON | 20 |
| 3 | hard| WITCH | 30 |
