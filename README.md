# これは何？

GWTでPolymer Elementsを使用するための習作。

# 制作手順

## セットアップ

`npm`は既にインストールしているものとする。
(注1: `npm`は[Node.js](https://nodejs.org/ja/download/)をインストールすれば付いてくる)
(注2: 今回Node.jsはオフィシャルサイトに書かれた手順でなく[nvm](https://github.com/creationix/nvm)を用いてインストールした)

作業用ディレクトリを作る:
<pre>
mkdir hello-polymer
cd hello-polymer
</pre>

`bower`をインストールする:
<pre>
npm install bower
</pre>

`bower`でPolymer-Elementsのうち今回使用するものをinstallする:
<pre>
 bower install PolymerElements/iron-list
 bower install PolymerElements/iron-input
 bower install PolymerElements/iron-autogrow-textarea
</pre>