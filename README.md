# Bland-Altmanプロットと系統誤差

ここでは、PythonのpyCompareライブラリを使用して、Bland-Altmanプロットのグラフ作成と系統誤差（比例誤差と固定誤差）を算出するコードを作成しました。以下に、実際に作成されるグラフやその作成手順を記載していますので、良かったら使ってください。

## 出来上がるグラフ

例えばこのようなグラフを作ることができます。（グラフは単独で保存できます）

- ↓サンプルグラフ⓵（系統誤差なし）
※p値の「2.6959e-1」は、科学的記数法（または指数表記）と呼ばれる表示方法です。この表記では、数値を基数（この場合は0.26959）と10の累乗（この場合は10の-1乗）で表現します。

![サンプルグラフ](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/assets/demo1.png)

- ↓サンプルグラフ⓶（系統誤差あり）

![サンプルグラフ](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/assets/demo2.png)


## 使い方手順

1. **データの準備**: グラフで使用するCSVファイルを用意してください。CSVファイルは、エクセルで作成した表データの保存時にCSV形式を選ぶだけでも可能です。
行や列ついては、以下のファイルの形式に沿って入力してください。
- [サンプルグラフ⓵のCSVファイル](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/detaset/deta.csv)

- [サンプルグラフ⓶のCSVファイル](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/detaset/deta2.csv)


サンプルグラフのCSVファイルは赤丸の場所からダウンロードできます。

![画像１](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/assets/demo3.png)


- 次に、後で使うので、↓こちらのファイルを押してから
- [Pythonコードのファイル](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/bland_altman.ipynb)

- この赤丸の場所を押してbland_altman.ipynbというファイルをダウンロードしておいてください。
![画像３](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/assets/demo4.png)

2. **Google colaboratoryの利用**: 次にこちらのツールを使います。今回の作業は無料で可能。

- [Google colabのサイトへ行きます）](https://colab.research.google.com/?hl=ja)
Googleアカウントが必要です。

- そして↓アップロードを押す。
![画像４](https://github.com/PT-Araisan/scd-mltbs-graph/blob/main/assets/demo2.png)
もしくはファイルのタブから『ノートブックをアップロード』を押す。

- さっきダウンロードしたbland_altman.ipynbをアップロードしてください。

すると、↓このような画面になります。そこで

- ⓵を押すと⓶が出てきます。少し時間がかかることがあります。５秒くらい。

- ⓶を押して、グラフを作りたいCSVファイルをアップロードしてください。

![画像４](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/assets/demo5.png)


- 最後に、↓の画像の'hoge.csv'のところを、自分がアップロードしたファイルの名前に変更して、上の赤丸の△ボタンを押します。Ctrl + Enterでもいいです。
![画像５](https://github.com/PT-Araisan/BlandAltman-SystematicError/blob/main/assets/demo6.png)

3. **グラフが表示されたら、右クリックで画像を保存してください**


## 補足事項

- お時間ありましたら、こちらのBland-Altmanプロットに関する論文も読むことをお勧めします。[Statistical methods for assessing agreement between two methods of clinical measurement](https://pubmed.ncbi.nlm.nih.gov/2868172/)

## お問い合わせ

何か質問や要望があれば、[Twitter の DM](https://x.com/Pt96442837Pt) からお気軽にお知らせください。
