# dockerでpython開発環境をお手軽に構築するテンプレート

 - Dockerとdocker-composeインストール後にdocker-compose.ymlのあるディレクトリで下記の手順でコンテナ起動
```
$ docker-compose up -d
```
 - コンソールにはdocker-compose.ymlのあるディレクトリで下記の手順で接続
 ```
$ docker-compose exec python3 bash 
```
