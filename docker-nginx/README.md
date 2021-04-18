```bash
# ビルド
$ docker build --tag hello-nginx .
# 確認
$ docker images -a hello-nginx
# 起動
$ docker run -d --name hello-nginx-container -p 80:80 hello-nginx
# 停止
$ docker stop hello-nginx-container
# 削除
$ docker rm hello-nginx-container
```