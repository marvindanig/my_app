# How this was set up:

```
$ rails --version
7.2.1

$ rails new my_app --skip-javascript -a propshaft

$ cd my_app && code .

$ bundle add importmap-rails

$ ./bin/rails importmap:install

$ bundle add stimulus-rails

$ ./bin/rails stimulus:install

$ bundle add turbo-rails

$ ./bin/rails turbo:install

```

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
