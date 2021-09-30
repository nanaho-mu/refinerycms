# README

[heroku](https://thawing-brook-87148.herokuapp.com/)です

# インストール
フォルダで

```
docker-compose up --build -d
docker-compose run web rails db:migrate
docker-compose run web rails db:seed
```

したら http://localhost:3000/ に出ます

http://localhost:3000/refinery でユーザー登録になります
