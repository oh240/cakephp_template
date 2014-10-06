## 必要な環境
- php5: 5.3以上(Composer)を使用するため
- php5-mcrypt
- php5-sqlite(テスト用のデータベースとしてSqlite3を使用しています)
- Composer(パッケージ管理にComposerを使用しています)

## 概要
簡単にcakeのテスト環境をさくっと立ちあげれるようにしてみました。

gitを使用した方法等の管理方法が過去に投稿されていますが、Composerを使用した形が一番簡単そうです。

プラグインの開発用や検証用にいいのではないでしょうか。

## 使用方法
1. git clone git@github.com:oh240/cakephp_template.git
2. cd cakephp_template
3. php composer.phar install
4. Console/cake server -p 9999
5. ブラウザからlocalhost:9999に接続する

## 主なパッケージ
- cakephp 最新安定版
- phpunit/phpunit 3.7.*
- cakephp/debug_kit 2.2.*
