# 定例WordPress講座 - 導入編

## スライドと動画
[スライドはこちら](https://speakerdeck.com/oleindesign/wordbenchqi-fu-ding-li-wordpressjiang-zuo-dao-ru-bian)

[![定例WordPress講座 - 導入編 動画](https://img.youtube.com/vi/NmEMwqQyMCE/0.jpg)](https://www.youtube.com/watch?v=NmEMwqQyMCE)

## WordPressとは

### WordPressって何？
誰でも無性で利用できるブログやウェブサイトを制作・管理できるCMSソフトウェアで、全世界の1/4のウェブサイトで使われています。

### WordPres.orgとWordPress.comの違い
WordPress.orgはインストール型。プラグインやテーマは自由に利用することができる。

WordPress.comはレンタルブログ型。テーマやプラグインの選択肢に限りがある。

### WordPressの自由とは
ライセンスはGPLv2またはそれ以降。コピーレフトという考え方が用いられる。

WordPress Foundationの役割について。「オープンソース、GPLソフトウェアを通じて、パブリッシングを民主化すること」が使命。WordCampの運営を資金面でサポートしている。

## ローカル開発環境を作ってWordPressを動かしてみる
>ローカル開発環境を動かして実演しながら講座を進めます。講座に沿って同じように自身の手元で試してみたい場合にはPCを持参ください。
>
>また、ローカル開発環境で使うアプリについては事前にダウンロード＆インストールをお願いします。（下記参照）

### ローカル開発環境とは
ローカル開発環境とは、自身のPC内にもう一つ別のPCを作り、その中に作業環境を構築するというようなイメージで解釈してもらっていいかと思います。

実際には、インターネットを経由してコントロールができるサーバーを利用して実験を行うことも可能です。

しかし、実際にはすでに運用を開始しているサーバーであったりすると、何かトラブルが起きた際に他のディレクトリを含むサーバー全体に悪影響を及ぼす可能性が考えられます。

ですので、実験やテストを気兼ねなく行うためにも、実際の運用サーバーとは切り離したローカル環境（自身のPC内）に環境を作ることが勧められています。

ローカル開発環境を整える方法はたくさんあります。例えばこんなものがあります。

* [vccw](http://vccw.cc/)
* [MAMP](https://www.mamp.info/en/)
* [Local by Flywheel](https://local.getflywheel.com/)

今回、こちらでは一番シンプルにWordPressを自身のパソコン内で立ち上げられるLocal by Flywheel（以下、Flywheel）を利用してみることにします。

では、実際にWordPressを動かせるローカル開発環境を用意してみましょう。

### Local by Flywheel をダウンロードする
まずは下のURLからアクセスして、Local by Flywheel という無料アプリケーションをダウンロードします。

> [https://local.getflywheel.com/](https://local.getflywheel.com/)

上のURLをクリックするとこのようなページが表示されます。
