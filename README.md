# Ruby on Rails チュートリアル

##  ダウンロードと起動方法

```
$ git clone git@bitbucket.org:ht0919/hello_app.git
$ cd hello_app
$ bundle install --without production
$ bundle exec rake db:migrate:reset
$ bundle exec rake db:seed
$ bin/rails s
```

## アクセス方法

1. ブラウザを起動
2. アドレス欄に「http://localhost:3000/」と入力
