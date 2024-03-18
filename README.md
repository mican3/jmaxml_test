# 気象庁防災情報XMLフォーマット形式電文のテスト用Atomフィード 

このAtomフィードは、CFM Weatherのテスト用です。 
情報は更新されることはなく、現在の気象/災害情報を示すものではありません。
また、気象庁が提供しているものではありません。  

以下がテスト用フィードのURLです。
- 高頻度（随時）        [https://mican3.github.io/jmaxml_test/extra.xml](https://mican3.github.io/jmaxml_test/extra.xml)
- 高頻度（地震火山）    [https://mican3.github.io/jmaxml_test/eqvol.xml](https://mican3.github.io/jmaxml_test/eqvol.xml)

このテスト用のフィードに掲載されている電文は、
[気象庁防災情報XMLフォーマット　技術資料](https://xml.kishou.go.jp/tec_material.html)　に掲載されている「サンプルデータ（令和6年3月15日一部更新）」を使用しています。

<!-- 
# サーバーの建て方
Live Seever を起動するのが楽。（VS Code の拡張機能）
https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

アドレスは、
http://127.0.0.1:5500/

# データの追加
1. dataフォルダにXML電文を入れる
2. Atomフィードで以下の置換を行う。

https://www.data.jma.go.jp/developer/xml/data/

↓

http://127.0.0.1:5500/data/ -->