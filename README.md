# penpa-edit
万能ペンシルパズルエディタ。
あらゆる正方形盤面のパズルを作図するためのソフトです。
記号の配置を工夫すると、3次元形状やピラミッド型など、一部の特殊な形状のパズルも作図できます。

画像保存とテキスト保存が行えます。出力されたアドレスをアドレスバーに入力することでロードされます。

## 対応ブラウザ
* Google Chrome (最新安定版)
* safari
* firefox

## ショートカットキー
* Ctrl + z : 一手戻る
* Ctrl + y : 一手進む
* Ctrl + d : 盤面を複製
* Ctrl + space : 数字と記号を同時に削除

## Tips
* 黒マス：右クリックで緑マスを入力。色は変更不可。
* 数字：キーボードで任意の文字を入力。特殊文字：パネルの「A」タブで半角スペース(" _ "で表示)が入力可能。「ア」タブでカタカナ入力可能。
* 数字>矢印 : マスをドラッグした方向に矢印が入力。
* 数字>Tapa : このモードのみ"."を空白文字として認識。空白含めた4文字を入れることで、上下左右に寄っている文字が入力可能。
* 記号：数字キーの1-9,0によって入力。パネルで入力できる記号の一覧を表示。左上から1,2,...と対応。
* 記号>図形>十字など、いくつかの記号はonoffの入力形式。特殊例：デジタル（枠）で同じキーを二回押せば枠だけ表示される。
* 特殊：入力した記号の根本のマスをクリックすることで削除。
* 特殊：入力中に通った道を戻ることで先端の位置を一手前に戻せる。

## 現在の機能
### 黒マス
* 黒マス。スタイルで色を選択。灰色は二色。（ぬりかべ、アイスバーン、シャカシャカ etc.）
* 濃灰のみ、二回クリックすると緑マスに。
### 線
* 通常：マスの中央をタテヨコに結ぶ線。（ましゅ、橋をかけろ、回文数独etc.）
* 対角線：マスの中央をナナメに結ぶ線。（Zigzag etc.)
* 自由線：任意のマス同士を結ぶ線。
* 補助x：辺に置く補助用のバツ記号
* スタイルで線の種類を選択。
### 辺
* 通常：マスの頂点をタテヨコに結ぶ線。（へやわけ、スリザーリンクetc.）
* 対角線：マスの頂点をナナメに結ぶ線。（対角線数独etc.）
* 自由線：任意のマスの頂点同士を結ぶ線。（鋭直鈍ループetc.）
* スタイルで線の種類を選択。
### 壁
* マスの内部にタテヨコで描かれる線。（縦横さん、スラローム etc.）
* スタイルで線の種類を選択。
### 枠
* 複数のマスを囲む線。（キラー数独 etc.）
* スタイルは点線と灰色の実線の二種類。
### 数字
* 通常：数字、アルファベット、一部の記号文字。パネルを使うとカタカナ入力も可能。（ぬりかべ etc.）
* 矢印：矢印付き文字。（ヤジリン、CastleWall etc.）
* 1/4：四隅の文字。（カックロ、ヘヤジリン、キラー数独 etc.）
* Tapa：Tapa用文字。4文字まで。
* 中、小：小さいサイズの数字。サイズは記号>円などの中、小と対応。
* 候補：数独など、ラテンスクエア用の候補数字。1-9に対応。onoff入力。
### 辺数字
* 文字を辺上、頂点に配置。
* 長文：長い文章。シークワーズなどのリストが作成可能。
### 記号
* 多数の記号。パネルを開くことで入力可能な記号を閲覧可能。〇や□などの図形、不等号、デジタル数字、その他パズル固有の記号など。
* スタイルで、図形を線の手前側に置くか、奥側に置くかを選択可能。（ましゅの〇は線の奥、ごきげんななめの〇は線の手前）
### 辺記号
* 記号を辺上、頂点に配置。
* ２つの記号をマスの中で重ねたい時にも使用可能。
### 特殊
* 複数マスにまたがる特殊記号。（アロー数独、サーモ数独、移動用矢印）
### グリッド
* 盤面の枠線を「新規作成・枠変更」ボタンから変更可能。
* 余白：盤面のグリッドの外側に数字を置く場合などに使用。（ビルディングパズルetc.）
* グリッド：内部の線種の選択、実線、点線、消去。
* 格子点：格子点の有無。（スリザーリンクetc.）
* 外枠：グリッド外枠の有無。
* 特殊な盤面形状の場合、全てをなしにした状態で、辺を使ってグリッドを自作可能。記号>図形>正方形>特大から、マスを直接描ける。

## 履歴
* 2019/07/14 ver1.01
* 2019/07/13 ver1.00
* 2019/07/07 β版
