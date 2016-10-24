# ニコ生駆動開発の概要

ニコ生駆動開発とは、自作ゲームのプレイ実況を行うニコ生配信を行うための、自作ゲーム開発を行う開発手法である。   
やたら難しい書き方しているけど、簡単に言ってしまえば自分で作ったゲームでプレイ実況配信をするから、  
それに向けてゲーム作るよという話である。   

このプロジェクトを通じて、社員個人のの開発スキル向上、部署間を超えたコミュニケーションの確立、  
社内でGit使える人少すぎ問題の解消など様々な目的はあるが、  
Unity使ったら簡単なゲームならすぐに作れるし、作ったゲームニコ生配信したら面白そうだからやってみた程度の実験的企画。  
何が起こるかはわからん  
## ニコ生配信について
月に1回ぐらいのペースで行います。  
次回配信は2016年10月27日  
[配信枠 http://live.nicovideo.jp/watch/lv279897148](http://live.nicovideo.jp/watch/lv279897148)  
配信は<a url=http://ch.nicovideo.jp/sonorite/live>ソノリテ公式チャンネル</a>で行っています。  
みんな見てね!!


## 作成したゲームたち
ここにある[https://github.com/nikonamakudou/games](https://github.com/nikonamakudou/games)  

## 開発環境
- Unity5
- ソースコードの管理はGitHubアカウント作ってを各自で行ってね


## 開発要件
- 作成するゲームのプレイ環境はPCを想定している
 - ブラウザ上でプレイを可能にするため、WebGLビルドを行う。
 - 作成したゲームはGitHubの`gh-pages`ブランチを使用して公開する予定  
 参考リンク  <a url=http://qiita.com/tanaka_lit/items/c32760e1cc2ba01e8f9a>` UnityのWebGLで書きだしたゲームをGitHubを使って公開する` </a>   


- 開発するゲームのジャンルは自由  
  オリジナリティあふれるゲーム 、おもしろいかどうかはあまり重要じゃない   
    ただし、配信できないような内容(R18等)はNG  
    あとは個人の良識に従います

## 環境構築
### Unityのインストール
インストール先URL  
[`https://store.unity.com/ja`](https://store.unity.com/ja)  

webGLビルドオプションを有効化する  
インストール時に「WebGL Build Support」にチェックを入れておくと幸せになれるから忘れないように  
参考  
[`Unityメモ】WebGLでビルドしてブログに載せる`](http://b-shiki.hatenablog.com/entry/2016/01/12/034021)  


### Gitのインストール  
注意  
事前にGitHubのアカウントを作成する  
 [`Githubのアカウント作成方法`](http://qiita.com/rshibasa/items/f62db870ed573ca4dced)  

#### GUIツールを使う人  
Git使ったコトない人やCUIコワイっていう人はこちら
- Source Treeのインストール  
  [`Gitを視覚的に操作できる「SourceTree」のインストール方法`](http://nelog.jp/sourcetree)  

- sshキーの設定  
  sourcetreeを結局使ってないからよくわかんない(´・ω・｀)  できたひとおしえて

#### CUIで大丈夫な人
GUIとかいらねぇていう人はこちら
- Gitのインストール  
[`初心者でもWindowsやMacでできる、Gitのインストールと基本的な使い方`](http://www.atmarkit.co.jp/ait/articles/1603/31/news026.html)  
sourcetree使う人もローカル版Gitを入れておいた方が便利かも

- sshキーの設定  
  [`Windows7からGitHubへSSH接続する手順(プロキシ環境有)`](http://qiita.com/bu-son/items/2efc10a18d7a46f14555)  
  Win8とかも同じ手順でいけるとおもう、たぶん

#### Gitってなんぞやっていう人向けの話
このへんを読んでおくといいよ、GUIのある無し関係なくやっていることは同じだよ  
  - [初心者の初心者による初心者のためのGit入門](http://qiita.com/novl/items/5491b4bb87170aa58a2e)    

- [【連載Git入門 第1回】SourceTreeでGitを始めよう！Gitで何ができるの？](http://naichilab.blogspot.jp/2014/01/git-1sourcetreegitgit.html)  

## スポンサー
株式会社ソノリテ  
[http://www.sonorite.co.jp/index.html](http://www.sonorite.co.jp/index.html)  

## お問い合わせ
t-zouchi  
mail: t-zouchi@sonorite.co.jp
