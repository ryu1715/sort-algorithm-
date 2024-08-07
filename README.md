## 実装したソートアルゴリズム
1. バブルソート
2. クイックソート

## それぞれの好きな理由
- バブルソート
  - シンプルで理解しやすい
    - 仕組みとしてもシンプルですし、コードで書いてみてもシンプル。「アリゴリズムとは何ぞや」みたいな状態でも理解しやすかった。
    - 単純に隣接した要素を交換するという単純な仕組みで、やはりアルゴリズム初学者に優しい！！！
- クイックソート
  - 分割統治法の美しさ
    - クイックソートはコードを書くまでは、バブルソートやその派生のソートアルゴリズムと比べても少し特殊な仕組みだったので気づかなかったのですが、コードで書いてみると問題を再帰的に小さく分割して処理する手法がとても美しいと感じた。
  - 実用性の高さ
    - 安定性こそ懸念点としてあるものの、平均計算時間から見ても効率的ですしメモリ効率もいいので、さまざまな言語の実装であったりライブラリ等で広く使われている点から見て実用的。

## コードの実行
- 実行環境
  - Python: 3.9.6

```shell
# バブルソート実行
$ python bubble.py

# クイックソート実行
$ python quick.py

# テストコード実行
$ python -m unittest test.py
```

## 参考
>- [クイックソート攻略してみた](https://zenn.dev/forcia_tech/articles/20230208_matsukawa)
>- [ソートアルゴリズム徹底解説: 各ソートの実装と比較](https://zenn.dev/brainyblog/articles/sort-algorithms-explained)
