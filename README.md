# GAE_default
GAE環境で、ネット上にアプリを作れたやつ。

https://cloud.google.com/appengine/docs/standard/python3/building-app/writing-web-service?hl=ja
これ通りに作って、requirements.txtのflaskのバージョンだけエラー出るから、普通に「flask」の記入だけにしたら通る。

gcloudで動かすアプリをちゃんと使いたいやつに変更するのを忘れないように。
gclould コマンドで操作したいプロジェクトのプロジェクトIDを指定する
$ gcloud config set project [PROJECT ID]
