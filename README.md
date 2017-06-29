Seminar Template 2016
=====================
2017 年度ゼミナール報告書のテンプレートです。

|ファイル名|説明|
|:--:|:--:|
|a4jsme.sty|A4 版のスタイルファイル|
|epic.sty|PiCTeX のマクロファイル|
|eepic.sty|拡張 PiCTeX のマクロファイル|
|jsadd.sty|`jsmepaper.sty` の補助ファイル|
|jsme10.sty| 10 point 文字の設定ファイル|
|jsmefont.sty| jsmepaper 使用のフォント設定ファイル|
|jsmepaper.cls|jsmepaper の LaTeX2e スタイルファイル|
|main.tex|メインのTeXファイル|
|src/*|この中の個別のTeXファイルに書いていく|

How to use
----------
### for \*NIX users
好きな方法でタイプセットすればいいと思いますが、`latexmk` をおすすめします。

```
latexmk -pvc main.tex #=> output: main.pdf
```

### for Windows users
手元に環境がなかったので、タイプセットできるか試していません。どなたか試してみて、問題があれば教えて下さい。対応します。

### eps 画像がずれる問題
`graphicx` パッケージの読み込みオプションに `dvipdfmx` ドライバが指定されていれば問題なく配置されるはずですが、TeX Live のバージョンによっては挙動が変わるかもしれません。ちなみに僕の環境は、TeX Live 2015 です。TeX Live 2016 などに関しては挙動を確認していませんので、うまくいかない場合には教えて下さい。
