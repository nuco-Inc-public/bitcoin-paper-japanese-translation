# 9. 値の結合と分割

個別にコインを処理することは可能であるが、転送の1セント毎に個々にトランザクションするのは扱いづらい。値を分割して結合するために、トランザクションには複数の入出力が含まれる。通常、より大きな前回のトランザクション、少量を組み合わせた複数のの入力、のいずれかがあり、最大で2つの出力がある。支払いの出力、もしあればお釣りの出力、である。

![transaction](https://github.com/nuco-Inc-public/bitcoin-paper-japanese-translation/blob/master/images/figure9.png "transaction")

トランザクションが複数のトランザクションに依存し、それらのトランザクションがさらに複数のトランザクションに依存する、というファンアウトはここでは問題でないことに注意すべきである。トランザクション履歴の完全な単体のコピーを抽出する必要性は決してありません。