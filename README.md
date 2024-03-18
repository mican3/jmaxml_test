このAtomフィードは、CFM Weatherのテスト用です。 
内容は更新されることはなく、現在の気象/災害情報を示すものではありません。
また、気象庁が提供しているものではありません。  

- 高頻度（随時）        https://mican3.github.io/jmaxml_test/extra.xml
- 高頻度（地震火山）    https://mican3.github.io/jmaxml_test/eqvol.xml


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