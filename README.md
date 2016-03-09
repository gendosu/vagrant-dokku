## README

vagrantでdokkuの環境を構築します。

## How to Use

* vmの起動  
  vagrant up --provision
  
* vmのIPの確認  
  vagrant ssh  
  $> ifconfig eth1

* dokkuの初期設定  
  http://[vmのIP]/  
  にアクセス

* 完成

* ローカルマシンにdokkuコマンドをインストール  
  http://dokku.viewdocs.io/dokku/community/clients/

* アプリのデプロイ  
  http://dokku.viewdocs.io/dokku/application-deployment/
