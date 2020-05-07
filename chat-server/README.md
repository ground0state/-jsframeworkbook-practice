# API 一覧

チャンネル追加。

```bash
curl -H 'Content-Type:application/json' -d '{"cname":"general"}' http://localhost:5000/chat-server-xxxxx/us-central1/v1/channels
```

チャンネル一覧。

```bash
curl http://localhost:5000/chat-server-xxxxx/us-central1/v1/channels
```

メッセージ追加。

```bash
curl -H 'Content-Type:application/json' -d '{"body":""}' http://localhost:5000/chat-server-xxxxx/us-central1/v1/channels/general/messages
```

メッセージ一覧。

```bash
curl http://localhost:5000/chat-server-xxxxx/us-central1/v1/channels/general/messages
```

リセット。

```bash
curl -H 'Content-Type:application/json' -d '{}' http://localhost:5000/chat-server-xxxxx/us-central1/v1/reset
```
