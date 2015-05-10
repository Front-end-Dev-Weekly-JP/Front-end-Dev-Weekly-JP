title: "[翻訳]Issue 53"
date: 2015-04-28 00:00:00

---
Front-end Dev Weekly Issue 53の元記事は[こちら](https://frontenddevweekly.curated.co/issues/53)

### コメント
<hr>
**Fast apps fast、つなぎ目のない変化、プリプロセッサのパフォーマンスにおける落とし穴**
Googleのようなビッグネームが頻繁に[新しいフレームワーク](http://foam-framework.github.io/foam/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)を出すのはなかなかないことです。特に、MVCのJSのフレームワークにおいては。しかし、このフレームワークはMVCであり、MVVMではありません。このフレームワークの意図する所を見ると、私は[Meteor](https://www.meteor.com/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)を強く思い起こします。
他の興味深い記事は[DEGのポストプロセッサ](http://www.degdigital.com/blog/returning-to-real-front-end-code?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)のものです。私はSassのプリプロセッサに多くの時間を費やしましたが、なぜポストプロセッサについてはあまり語られることがないのでしょうか。私が思うに、皆はインターネットやブラウザのレンダリングの速度は一定の割合で増加し続け、私たちのパフォーマンスが低いCSSをカバーしてくれると望んでいるからでしょう。それは信頼できるのでしょうか。クリーンアップしましょう！

[Galen Vinter](https://twitter.com/gvinter)

<hr>

### フレームワーク
<hr>
**[Googleによる、FOAMフレームワーク](http://foam-framework.github.io/foam/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
彼らのGitHubや説明のサイトを見ると重いですが、このMVCフレームワークは"fast apps fast"の"基本原理"のもと、Googleによってもたらされています。
[github.io](http://foam-framework.github.io/foam/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)

<br>
### UI/UX
<hr>
**[設定ファイルを用いたSassによるテーマ付け](http://www.sitepoint.com/sass-theming-withconfiguration-files/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
私が[Placester](https://placester.com/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)にいたとき、何年もサイトのテーマ付けのために働きました。事前に作られたサブテーマは戦いのたった半分だったにも関わらず（もう半分はユーザーに色やテーマの要素を使用するのを許可することでした）、Sassによるテーマ付けは確実に未来の頭痛のタネを無くすのにいい時間です。
[sitepoint.com](http://www.sitepoint.com/sass-theming-withconfiguration-files/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)

<br>
### ライブラリ
<hr>
**[WheelNav.js - 私たちのための円や回転のライブラリ](http://wheelnavjs.softwaretailoring.net/examples.html?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
私はこのライブラリが好きです。なぜなら、今までに触ったことのないつなぎ目の無い形や相互作用の世界の扉を開いてくれたからです。
[softwaretailoring.net](http://wheelnavjs.softwaretailoring.net/examples.html?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)

---

**[Sprint.jsのようなものでJQueryの代替を考える](https://github.com/bendc/sprint?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
「SprintはJQueryの代替です。後継者ではありません。JQueryにはもっと特徴があり、さらにエッジなケースにも対応しますし、さらに多くのブラウザをサポートします。Sprintはパフォーマンスを犠牲にすることなくDOMをフレンドリーにする薄いレイヤーです。」
[github.com](https://github.com/bendc/sprint?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)

<br>
### 学習
<hr>
**[CSSのポストプロセッサやJSのトランスパイラについて知っていますか？ここから始めましょう...](http://www.degdigital.com/blog/returning-to-real-front-end-code?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
プリプロセッサは私が覚えている限りでは、一番流行したものです。しかし、アップストリームのプリプロセスがダウンストリームのパフォーマンスに影響を与えるのは簡単です。どのようにそれが起きるのか、どうやってパフォーマンスの落とし穴を避けることができるか学びましょう。
[degdigital.com](http://www.degdigital.com/blog/returning-to-real-front-end-code?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)

---

**[プロセスのどこにスタイルガイドを差し込むか](https://css-tricks.com/where-style-guides-fit-into-process/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
明らかなようにも思えますが、プロセスのどこにスタイルガイドは差し込めるでしょうか。Chris Coyierには考えがあるようです。
[css-tricks.com](https://css-tricks.com/where-style-guides-fit-into-process/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)

---
**[Ruby Sass, LibSass – 違いは何でしょうか？](http://sassbreak.com/ruby-sass-libsass-differences/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
プロのフロントエンド開発者ならこれらの2つの"Sass"のライブラリの違いについて知っておくべきです。
[sassbreak.com](http://sassbreak.com/ruby-sass-libsass-differences/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)

<br>
### レスポンシブ
<hr>
**[Sassとレスポンシブなタイポグラフィー](http://www.sitepoint.com/sass-responsive-typography/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)**
次回、私は新規開発のプロジェクトでデザイナと働きます。そこでは、フォントのサイズを少ししか使わないことにチャレンジしようと思っています。この方法によって、デザイナは簡単にSassのMapや適用されているレスポンシブを理解できます。
[sitepoint.com](http://www.sitepoint.com/sass-responsive-typography/?utm_campaign=Front_End_Dev_Weekly_53&utm_medium=email&utm_source=Front%2BEnd%2BDev%2BWeekly)