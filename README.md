# こうかとん探検隊
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
こうかとんが洞窟の中の敵を倒しながら探索するゲーム
敵をすべて倒すとクリアになる。方向キーで移動し、スペースキーでジャンプ。
sキー、aキーを押すと玉を発射し敵を倒すことができる。
ライフがなくなるとゲーム終了

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
* Shot_a:ビームが斜めに出るようになり、2回壁を跳ね返ることができる。(担当:松岡)
* トラップの作成(担当：小野塚)
* 敵の射撃追加(担当：小野塚)
* こうかとんの残りライフを表示するKokaton_Lifeクラス(担当：石原)：画面上に残りライフを表示する
* BGMを追加する（プレイ時、弾を打ったとき、ダメージをくらったとき）(担当:梅田)
* 残り敵数の表示するRemaining_Enemiesクラス(担当:佐柄)
* メインループ内でゲームクリア演出の作成(担当:佐柄)
### ToDo
- [ ]Shot_s, Shot_aで発生するビームの向きを変更 
- [ ] マップの完成
- [ ] 敵の射撃追加
- [ ] 色と表示位置の変更
- [ ] HP制度ではなく残機制度にできないかの模索
- [ ] BGMが同時に複数再生できるようにする。
- [ ] ゲームクリア演出の作成
- [ ] Remaining_Enemiesクラス内の変数名の統一
### メモ
* 'W'をマップに指定するとトラップがおける
* 参考URL
【Pygame】Pythonでゲームを作る -3Days-
https://cpp-learning.com/wp-content/uploads/2018/11/Pygame_3Days.html