## 概要
デイトラにて学習中に作成した別のミニゲーム「EnemyDown」のDB上にある難易度設定を取得、更新、追加するアプリです。

## 開発環境
- Java 21
- MySQL 8.0.43
- SpringBoot 3.5.6

## データベースの情報
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
| 1 | easy | ZOMBIE | 10 |
| 2 | normal| SKELETON | 20 |
| 3 | hard| WITCH | 30 |
