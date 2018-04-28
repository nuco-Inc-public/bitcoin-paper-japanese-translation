# 3. タイムスタンプサーバー

我々が提案するソリューションはタイムスタンプサーバーから始まる。タイムスタンプされるアイテムのブロックのハッシュを取り、新聞やUseNetのように広く公開することにより機能する。ハッシュに入るためには、明らかに、その時間にデータが存在しなければならないことを証明する。それぞれのタイムスタンプは鎖を成す形でそれ以前のタイムスタンプを内包し補強する。

![timestamp-server](https://github.com/nuco-Inc-public/bitcoin-paper-japanese-translation/blob/master/images/figure3-1.png "timestamp-server")