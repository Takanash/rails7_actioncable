# README
rails7 x Websocket sample

参考: [Rails7でさくっとWebSocketする](https://zenn.dev/seita1996/articles/rails7-actioncable)

# 動作手順

```bash
docker compose build
docker compose run --rm app bundle exec rake db:create
docker compose run --rm app bundle exec rake db:migrate
docker compose up app
```

http://localhost:3000/
を2つのタブで開き、片方のタブで投稿したメッセージがもう片方のタブにリアルタイムで反映されていることが確認できればOK
