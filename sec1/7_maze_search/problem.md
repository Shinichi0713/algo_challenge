## 問題

入力された迷路からS(スタート)からG(ゴール)の最短の経路を見つけて、経路までの移動量を求めるプログラムを作ること

## 幅探索法

幅探索法（Breadth-First Search, BFS）は、グラフやツリーの探索アルゴリズムの一つで、最短経路を見つけるのに適しています。以下に、幅探索法の基本的な手順を示します：

1. **初期化** :

* 探索を開始するノード（スタートノード）をキューに追加します。
* 各ノードの訪問状態を記録するためのリストや配列を用意します。

1. **キューの処理** :

* キューが空になるまで以下の手順を繰り返します。
* キューの先頭からノードを取り出し、そのノードを訪問済みとしてマークします。
* 取り出したノードに隣接するすべてのノードを調べ、まだ訪問していないノードをキューに追加します。

1. **探索の終了** :

* キューが空になったら探索を終了します。