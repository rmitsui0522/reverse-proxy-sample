# reverse-proxy-sample

HTTPS通信下でリバースプロキシを構成するサンプル

## サーバー

- Cent OS: 6
- apache: 2.2

## コマンド
起動
```
docker-compose up --build -d
```
停止
```
docker-compose down
```

## 設定
/docker/apache/httpd/conf.d/reverseProxy.conf 内のProxyPassを変更する

## 確認用URL
http://localhost:8080/example
