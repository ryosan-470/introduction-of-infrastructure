# infla-introduction

初めてのインフラ分野に手を出す人向けに書いた, インフラの教科書みたいなものです.
最初に仮想マシンに実際のOSをインストールして, Wordpressなどのブログサイトを自分のマシン上で構築することが目標です.

読みやすい形式になったドキュメントは [http://infla-docs.jtwp470.net](http://infla-docs.jtwp470.net) にて公開されています.

## 対象読者

* 初めてLinuxのサーバー版を使ってみたい人
* Webサーバー等を構築したい人
* インフラとはなにか知りたい人

## 必要なもの

* 計算機
    * ホストマシンのOSは特に指定しません.ただしVirtualBoxが動くマシン
* 最新版の[VirtualBox](https://www.virtualbox.org/)
    * 別にVMWareやHyper-Vでも良い.ただしその時はネットワークの設定などは自分で調べて適切にやって貰う必要があります.

## 前提知識
以下の知識が予め必要になります.これらの知識がない場合は一度それらを学んでから本書を読むことを薦めます.

* Linuxの利用経験. GUI版でも構わないができるかぎりCUIの利用経験があると好ましい.
* Linuxシェルの使い方など. 基本的なBashのコマンドを使いこなすこと.
* Vimやnano, Emacsなどのエディタの利用.
    * AtomやSublimeといったエディターは利用できないのでそれらの利用経験があると好ましい.
* ネットワークの基礎知識

## 目標

仮想マシン上に実際にOSをインストールしていき,ネットワークの設定を行い, 実際にLAN内で他人のマシンを閲覧したり, 自身のサイトが表示できることなどを確認します.更にWordpress等をインストールすることでそれっぽいWebサイトを簡単に構成します.

今回の内容ではインターネット上に公開しませんが, 実際に公開することを考えたセキュリティ設計等を行います.

## 質問, 問題点, 指摘など
すべての質問, 問題点, 指摘などはGitHubの[Issues](https://github.com/jtwp470/infla-introduction/issues)にお願いします.

## LICENSE

[![CC-BY-SA](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

## Author

[Ryosuke SATO](https://github.com/jtwp470)
