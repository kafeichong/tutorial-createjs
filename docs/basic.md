---
title: CreateJSとは
author: 池田 泰延
published_date: 2015-11-30
modified_date: 2019-01-10
---

## CreateJSとは

![CreateJSの導入編](../imgs/title_createjs.jpg "1280x400")

[CreateJS](https://createjs.com)は、HTML5でリッチコンテンツを制作するためのJavaScriptライブラリのスイート（特定用途のソフトウェアを詰め合わせたパッケージ）です。Flashデベロッパーとして著名な[Grant Skinner](https://twitter.com/gskinner)氏が代表を務める[gskinner](https://gskinner.com/)社が開発を行っており、オープンソースソフトウェアとして個人・商用でも無償で利用できます。

## CreateJS を構成する4つの JavaScript ライブラリ

CreateJSには、リッチコンテンツを制作するための複数のJavaScriptライブラリが含まれています。CreateJSはグラフィックの表現機能を中心に、リッチコンテンツを作るための統合的なソリューションが提供されているというのがポイントです。

- EaselJS	: HTML5 Canvasでの制作を扱うためのJSライブラリ。キャンバス(画布)に対するイーゼル(画架)を意図した名前になっています。
- TweenJS	: JavaScriptのトゥイーンエンジンです。モーション制作に役立てることができます。
- SoundJS	: サウンドを利用するためのJSライブラリ。簡単にクロスブラウザでの音声再生が実現できます。
- PreloadJS	: 素材（画像、音声、JS、データ）を先読みできるJSライブラリ。


## 類似技術との比較 - なぜ CreateJS を選ぶのか？

webページのリッチコンテンツを作るための技術はたくさんあります。スタイルシートとしてのCSS3、GPUを活用するWebGL、ベクター情報のSVG、プラグインシステムのFlash Player・・・など、例を挙げればきりがありません。CreateJSはHTML5 Canvasというテクノロジーを中心に構築されたフレームワークです。HTML5 Canvasは類似の技術と比べて次の特徴を持っています。

- グラフィック描画ができる
- 描画速度が非常に高速である
- 対応環境が幅広い (モダンブラウザであれば100%)
- いかなる表現も自由に作ることができる

では、デメリットはどの点にあるのでしょうか。処理性能面だけで言えばWebGLのほうが高速ですし、メンテナンスを考慮すればHTML5+CSS3のほうが適しているでしょう。しかし、WebGLは実装難易度が高く素材の取り回しの手間は高いスキルを必要とします。HTML5+CSS3は情報としてのwebページの制作には向いていますが、モーション実装においては自由度は十分高いとは言えません。このように、webのテクノロジーは一長一短であり、用途に応じて適した技術を選択するのが理想です。

HTML5 Canvasは2Dのインタラクションデザインという用途に適しています。この用途に限って言えば、学習のしやすさ、表現の幅広さ、処理性能、対応環境の充実度という点で、HTML5 CanvasをベースとするCreateJSに敵うソリューションはないでしょう。CreateJSはFlash時代から受け継がれるインタラクションデザインのナレッジがあり、カジュアルに作れる手軽さと強力な表現力を有しています。スポンサーにAdobeやMicrosoft、Mozillaが入っていることで業界の注目を集めており、将来性も期待できます。

なによりも、CreateJSを学ぶことでインタラクションデザイン全般に応用できる基礎力が身につきます。本サイトでは、HTML5 Canvas特有のテクニックよりも、インタラクションデザイン実装の基礎力を習得できることを中心にまとめています。それを学ぶことで異なるテクノロジーでも応用できるからです。ここで学ぶことは永遠の知的資産になるというマインドを持って、最後までぜひお付き合いください。


[次の記事へ](basic_showcase.md)
