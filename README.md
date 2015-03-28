# sinatra-heroku-skelethon
## Getting Start
```bash
$ bundle install --path vendor/bundle
$ bundle exec foreman start
```

## Deploy
```bash
$ git init
$ heroku git:remote -a checkkun
$ git add .
$ git commit -am "make it better"
$ git push heroku master
```

ref: http://qiita.com/gogotanaka/items/760d4e6ad2b19ff78ff9
