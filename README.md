# ggsample02

## ゲームグラフィックス特論　第２回　宿題

シェーダを使って図形を描いてください。

* 宿題のひな形を変更して課題の図形の正面図 (xy 平面への直交投影図) を描いてください。
* 宿題のひな形は [GitHub](https://github.com/tokoik/ggsample02) にあります
 (宿題のひな形で使っている[補助プログラムの解説](https://tokoik.github.io/gg/html/annotated.html))。
* 詳しくは[講義のスライド](https://tokoik.github.io/gg/ggnote02.pdf)を参照してください。

## 補足

このプログラムを実行すると、次のような図形が表示されます。

![このプログラムによる生成画像](images/ggsample02b.png "このプログラムによる生成画像") 

このプログラムを、次の図形の正面図を表示するように修正してください。

![表示する図形データ](images/ggsample02a.png "表示する図形データ") 

この画像が次のようになれば、多分、正解です。

![期待される結果](images/ggsample02c.png "期待される結果") 

* 頂点データの要素数が3（三次元）になっていることに注意してください。
* glVertexAttribPointer() の第2引数 size をそれに合わせる必要があります。
* ggsample02.cpp をアップローダで提出してください。
