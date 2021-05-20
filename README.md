# dockerでjupyterlab環境

## 動かし方

1. docker-compose.ymlがあるディレクトリ上で以下のコマンドを実行
2. ブラウザで`localhost:8888`にアクセス

```shell
docker-compose up -d
```

jupyter上で作成したファイルはnotebookディレクトリに保存される。
逆に扱いたいファイルはnotebookディレクトリに置くことで操作可能。

## 止め方

```shell
docker-conpose stop
```