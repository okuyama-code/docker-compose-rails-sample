## railsのテストを実行する
```
docker-compose ps
```
```
 docker ps -a
```
Exitedなら
```
docker start ca61f5c0ddab 2fc7deb96b6c
```
コンテナに入る
```
docker-compose exec web bash
```

testフォルダに既に用意されているtestスクリプトを実行する
```
rails test
```

## Travis CIのセットアップ
CIツール
