# Ruby on Rails チュートリアル

##  ダウンロードと起動方法

```
$ git clone git@bitbucket.org:ht0919/sample_app.git
$ cd sample_app
$ bundle install --without production
$ bundle exec rake db:migrate:reset
$ bundle exec rake db:seed
$ rails s
```

## アクセス方法

1. ブラウザを起動
2. アドレス欄に http://localhost:3000/ と入力

## Warning対策

1. Gemfileの下記の行を修正

```
gem 'sass-rails',   '5.0.2'
          ↓
gem 'sass-rails',   '5.0.6'

```

## クラウド環境での操作

1. サーバーの起動 → rails s -b $IP -p $PORT
2. ブラウザで確認 → https://rails-tutorial-ht0919.c9users.io/
