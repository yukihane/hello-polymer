# これは何？

GWTでPolymer Elementsを使用するための習作。

# 制作手順

## セットアップ

参考: https://www.polymer-project.org/2.0/start/install-2-0#use-bower

`npm`は既にインストールしているものとする。
(注1: `npm`は[Node.js](https://nodejs.org/ja/download/)をインストールすれば付いてくる)
(注2: 今回Node.jsはオフィシャルサイトに書かれた手順でなく[nvm](https://github.com/creationix/nvm)を用いてインストールした)

作業用ディレクトリを作る:
<pre>
mkdir hello-polymer
cd hello-polymer
</pre>

npmプロジェクトとして初期化:
<pre>
npm init
</pre>

`bower`をインストールする:
<pre>
npm install --save-dev bower
</pre>

bowerプロジェクトとして初期化:
<pre>
bower init
</pre>

`bower`でPolymer-Elementsのうち今回使用するものをインストールする:
<pre>
 bower install --save PolymerElements/iron-list
 bower install --save PolymerElements/iron-input
 bower install --save PolymerElements/iron-autogrow-textarea
</pre>

## 補足: `git clone` からの復元

本リポジトリを `git clone` して取得した場合は、 `npm` がインストールされている状態で次のコマンドを実行すれば必要なモジュールが取得できる(つまり、前節のセットアップを行った状態が復元できる):
<pre>
cd hello-polymer
npm install
bower install
</pre>
