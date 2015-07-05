title: "[翻訳]Issue 61"
date: 2015-06-30 00:00:00

---
Front-end Dev Weekly Issue 61の元記事は[こちら](https://frontenddevweekly.curated.co/issues/61)

### コメント
<hr>
**Googleが静かにGitHubの競合をリリースしました**
今週は、Sassのようなライブラリと、パフォーマンスとUXの面で私たちを助けてくれる賢いJSのライブラリと、Sublime Textを無償化させてしまうかもしれないAtomという新しいテキストエディタについて紹介します。個人的に、私はSublime Textユーザーなのですが、Atomが主張している通り素晴らしいものであれば、Atomに近々移るでしょう。乞うご期待...
また、私は読者のみなさんのことをさらによく知ろうと試みていますが、もしみなさんの中にフリーランサーやコンサルタントの方がいらっしゃいましたら、面白いと思うであろう[どうやって期限内にプロジェクトを完遂させるか](https://blog.projectpulse.io/complete-client-projects-on-time/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)という記事を最近書きました。もしこの記事に書いてあることを試した方がいらっしゃいましたら、コメント欄にそのように書いていただくか、[私にtweet](https://twitter.com/gvinter?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)してください。

[Galen Vinter](https://twitter.com/gvinter)

<hr>

### パフォーマンス
<hr>
**[Purify.css - 使われていないCSSを削除する](https://github.com/purifycss/purifycss?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)**
Purifyは「アプリケーションが使用しているCSSのセレクタを発見し、使われていないCSSを除いたファイルを作成」します。
[github.com](https://github.com/purifycss/purifycss?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)

---

**[Sassのライブラリをテストすること](http://www.sitepoint.com/testing-sass-library/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)**
「私が最近[5分でSassの関数をテストすること](http://www.sitepoint.com/testing-sass-function-5-minutes/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)という記事で紹介した、[SassyTester](https://github.com/HugoGiraudel/SassyTester?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)を使ってSassでテストが書かれる単純なものを私たちは求めていました。」
[sitepoint.com](http://www.sitepoint.com/testing-sass-library/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)

<br>

### 開発ツール

<hr>
**[Googleが静かにGitHubの競合をオープンしました](https://cloud.google.com/tools/cloud-repositories/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)**
Google Cloud Platformでホストされる、全ての機能を持ったプライベートなGitのリポジトリです。
[google.com](https://cloud.google.com/tools/cloud-repositories/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)

<br>

### 意見

<hr>
**[さらにセマンティックで整備されたJavaScriptのアプリケーションを書く単純な技術](https://medium.com/space-camp/three-simple-techniques-for-writing-more-semantic-and-maintainable-javascript-apps-206b4fb89f15)**
私は#2（JSのコードでIDを参照しない）に完全には賛成できなかったので、「学習」ではなく「意見」としてこの記事にマークをつけました。私は個人的にはスタイルにとってのクラスやJSにとってのIDを使い、特別な場合ではdata-*属性を使用します。なぜなら、そのJSがとても読みやすくなるからです。しかし、これはただの私の意見であることを再度お伝えします。そして、この記事の著者はさらに大きなアプリケーションにおいてはたぶん正しいのでしょう。
[medium.com](https://medium.com/space-camp/three-simple-techniques-for-writing-more-semantic-and-maintainable-javascript-apps-206b4fb89f15)

<br>

### UI/UX

<hr>
**[Sassのエステ第2弾:色とパレット](https://scotch.io/tutorials/aesthetic-sass-2-colors?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)**
「あなたは自分の色のパレットを選択して持っているでしょう。ビルトインのSassの色の関数はそれらを操作するために使用することができます。」
[scotch.io](https://scotch.io/tutorials/aesthetic-sass-2-colors?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)

---
**[Gradify - 画像からCSSでグラデーションを行う](http://gradifycss.com/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)**
私が[Placester](https://placester.com/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)で働いていた時、コンテンツにリーチしてフロントエンドを動的に構築していました。UXの大きな挑戦のうちの1つは、デザインや、使いたいコンテンツや画像は何でも使えるような多彩なUIを見つけることでした。このライブラリは、いつでもデザインの一部として画像を使うように計画されているかのように、どの画像を使うかの判断を助け、それに動的にグラデーションを行います。
[gradifycss.com](http://gradifycss.com/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)

<br>

### 学習

<hr>
**[Node.jsのイベントループを理解すること](https://nodesource.com/blog/understanding-the-nodejs-event-loop?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)**
この記事はNode.jsのイベントループの概要について教えてくれます。技術的な詳細については不足しています。Trevorが言及しているように、イベントループの「ユニコーンとと虹」について理解することで、「魔法をエンジョイしすぎるほどエンジョイでき」ます。
[nodesource.com](https://nodesource.com/blog/understanding-the-nodejs-event-loop?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)

<br>

### ニュース

<hr>
**[ハックできるテキストエディタであるAtomが1.0になりました](http://blog.atom.io/2015/06/25/atom-1-0.html?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)**
近年においてとてもよくウォッチされているテキストエディタの1つであるAtomがバージョン1になり、今やプロダクションでも使える準備ができたと開発者の世界を波立たせるようになりました。もしあなたが好むなら、アナウンスをスキップして、[こちらからダウンロード](https://atom.io/?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)できます。
[atom.io](http://blog.atom.io/2015/06/25/atom-1-0.html?utm_campaign=Front%2BEnd%2BDev%2BWeekly&utm_medium=web&utm_source=Front_End_Dev_Weekly_61)