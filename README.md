# LoLダメージ計算機

## 機能
- チャンピオンを選択し、コマンドバトルのような形でグラフィカルにダメージ計算を行える。
- ルーン、アイテム、バフ、スキルレベルを考慮する。

## DB設計

### Champions
| Name | Type | Index | Null | Unique | foreign_key |
|:-----|:----:|:-----:|:----:|:------:|:-----------:|
| id   |      |       |      |        |             |
| name |      |       |      |        |             |

### Items
| Name | Type | Index | Null | Unique | foreign_key |
|:-----|:----:|:-----:|:----:|:------:|:-----------:|
| id   |      |       |      |        |             |
| name |      |       |      |        |             |

### Runes
| Name | Type | Index | Null | Unique | foreign_key |
|:-----|:----:|:-----:|:----:|:------:|:-----------:|
| id   |      |       |      |        |             |
| name |      |       |      |        |             |
