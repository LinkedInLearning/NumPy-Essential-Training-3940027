# NumPy 基本講座
LinkedInラーニングの「Go言語 基本講座」コース用のリポジトリです。このコースは [LinkedInラーニング][lil-course-url]で視聴できます。

![Go言語 基本講座][lil-thumbnail-url] 
AIは画像や文章をベクトル化された多次元の配列として数値で記録します。PythonのNumPyライブラリはこの多次元の大量の数値を高速に扱うことができ、NumPyライブラリを学ぶことがAIを理解する第一歩になります。このコースではPythonのNumPyライブラリについて学びます。配列同士の結合や分割、行列を入れ替える転置などの操作、そして配列の要素をひとつひとつ取り出すことなく複雑な計算や関数を適用する方法を紹介します。このコースで学習すれば数字が苦手、計算が不得意と思っている方でも簡単に数値の配列を操作することができるようになります。

## リポジトリの使い方
このリポジトリには必要に応じてブランチが設けられています。ブランチのポップアップメニューを使用して、使用するブランチに切り替えたあとにコースを視聴してください。またURLに`「/tree/ブランチ名」`を追加することで、アクセスしたいブランチに移動することも可能です。

## ブランチ
ブランチはレッスンごとに作成されている場合があります。その場合はブランチ名に`「章番号_レッスン番号」`が付けられています。例えば`「02_03」`という名前のブランチは、2章の上から3番目のレッスン用のブランチとなります。

レッスン前と後のコードを格納しているブランチもあります。該当ブランチには「開始時」（beginning）を表す`「b」`と、「終了時」（ending）を表す`「e」` がブランチ名についています。`「b」`のブランチにはレッスン開始時点のコードが、`「e」`のブランチにはレッスン終了時点のコードが格納されています。また「main」のブランチにはコードの最終形が格納されています。

ファイルに変更を加えた後に、エクササイズファイルのブランチを次のブランチに切り替えたさい、次のようなメッセージが表示されることがあります。

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

この問題を解決するには：
	
    次のコマンドで変更を加えます：git add .
	次のコマンドで変更をコミットします：git commit -m "some message"

## インストール
### Anacondaをインストールする場合

1. 下記urlからAnacondaをダウンロードしてインストールしてください。
https://www.anaconda.com/download

2. Anacondaを起動してJupyter notebookを選択してください。

### Jupyter notebookだけをインストールする場合
1. ターミナルでpip install jupyterと入力してJupyter notebookをインストールしてください。

2. ターミナルでJupyter notebookと入力してJupyter notebookを起動してください


### インストラクター

**金宏 和實**

_株式会社イーザー副社長、テクニカルライター_

この講師の他のコースを視聴する：[LinkedInラーニング](https://www.linkedin.com/learning/instructors/21400000)

[lil-course-url]: https://www.linkedin.com/learning/numpy-essential-training-23166311/
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4E0DAQEiKBwbjZb74A/learning-public-crop_675_1200/learning-public-crop_675_1200/0/1735842803711?e=2147483647&v=beta&t=185iS45Hbt90SypN5OY20-IpWfo9Fzc_Ag7Yj3RYejU
