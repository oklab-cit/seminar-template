Seminar Template 2016
=====================
2016 年度ゼミナール報告書のテンプレートです。

|ファイル名|説明|
|:--:|:--:|
|a4jsme.sty|A4 版のスタイルファイル|
|epic.sty|PiCTeX のマクロファイル|
|eepic.sty|拡張 PiCTeX のマクロファイル|
|jsadd.sty|`jsmepaper.sty` の補助ファイル|
|jsme10.sty| 10 point 文字の設定ファイル|
|jsmefont.sty| jsmepaper 使用のフォント設定ファイル|
|jsmepaper.cls|jsmepaper の LaTeX2e スタイルファイル|
|main.tex|基本、こいつに書く|

How to use
----------
### for \*NIX users
好きな方法でタイプセットすればいいと思いますが、`latexmk` をおすすめします。

```
latexmk -pvc main.tex #=> output: main.pdf
```

### for Windows users
手元に環境がなかったので、タイプセットできるか試していません。どなたか試してみて、問題があれば教えて下さい。対応します。
