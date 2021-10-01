以下のバージョンを使用すること

```
"dependencies": {
        "express": "^4.17.1",
        "socket.io": "^2.3.0",
        "artillery": "^1.7.9"
    }
```

```
npm install //node_modulesインストール
node index.js //localhost:3000　起動
artillery run mychat_test.yaml //　テスト実行

```

callbackでnode.jsのエラー
https://stackoverflow.com/questions/67609088/socket-io-callback-is-not-a-function-error
https://github.com/socketio/socket.io-redis-adapter/issues/375
これに関連してるかも？

socket.ioのバージョンが2系だとエラー出るかも？

Artilleryから投げるとundefinedで出力される

```
name: kevin message: hello
undefined
user disconnected
name: j;aksgs message: alsdjkf
[Function]
```