# PythonSelenium


## 各コマンド

```
$ cd PythonSelenium
$ docker-compose build
$ docker-compose up -d                 # detouched mode option
$ docker-compose exec python bash      # 起動したpythonコンテナに入る 
```

## 実行

```
$ python /work/test.py
```

## pythonファイル実行中のChromeブラウザの挙動

ホストの適当なブラウザから
http://localhost:7900/?autoconnect=1&resize=scale&password=secret
にアクセスすることでリアルタイムで確認できる
