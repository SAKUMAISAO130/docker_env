# 開発環境構築用リポジトリです

基本laravel用の環境ですが、
laravelインストールはこのリポジトリで行っていないので、
laravel以外にも使えます。

参考ページ
https://qiita.com/yun-yzrh/items/2d5b24d9df30624ab6d2

https://qiita.com/yun-yzrh/items/d63b7e67256ed914deb8

https://qiita.com/yun-yzrh/items/2d3abcf1108b3a241f98

リポジトリをクローンしてきて、
下記コマンドでビルドします
> $ docker compose up -d --build

ビルドできたらコンテナに入って必要なフレームワークをインストールするか。
Gitリポジトリをクローンするかしてください。
> $ docker compose exec php bash
> $ composer create-project --prefer-dist "laravel/laravel=" .