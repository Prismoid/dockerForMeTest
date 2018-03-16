### ドッカーのイメージを表示
$ docker images

### ドッカーの使い方
# docker終了
$ docker kill [コンテナID/NAME]
# docker停止
$ docker rm [same as above]
# nginxの実行(8080番)
$ docker run -p 8080:80 nginx
# コンテナ一覧を表示
$ docker ps
# 他に色々
http://paiza.hatenablog.com/entry/docker_intro#commands_basic


