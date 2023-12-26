# こうかとん探検隊
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターこうかとんを十字キーを使って操作し、敵を全て倒したらクリア

## ゲームの実装
###共通基本機能
* ステージのブロック情報に関するBlockクラス
* 敵の状態や移動に関するEnemyクラス
* 球に関するShotクラス
* 主人公キャラクターに関するKokatonクラス
* マップに関するMapクラス
* 画像を読み込むためのload_image関数
* ゲーム実行に関するKokaton_Gameクラス
### 担当追加機能
* 残り敵数の表示するRemaining_Enemiesクラス
* メインループ内でゲームクリア演出の作成
### ToDo
- [ ] ゲームクリア演出の作成
- [ ] Remaining_Enemiesクラス内の変数名の統一
### メモ
* 参考URL
【Pygame】Pythonでゲームを作る -3Days-
https://cpp-learning.com/wp-content/uploads/2018/11/Pygame_3Days.html

