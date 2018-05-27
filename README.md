# README

シンプルな Ruby on Rails でできた掲示板アプリです。

# 使い方

```
docker-compose build
docker-compose up -d
docker-compose run web bundle exec rake db:create
```

http://localhost:3000/boards でアクセスできます。
