# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

---

ActiveRecord:: NoDatabaseErrorUnknow
 ->
 [Exsample](https://eri2490.hatenablog.com/entry/2020/02/17/235604)

``` 
$ docker-compose run --rm web rake db:create
$ docker-compose run web bin/rails db:migrate RAILS_ENV=development
```
