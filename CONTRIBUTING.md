# Contributing

## Running tests

### Install prerequisites

Install the latest version of [Bundler](http://bundler.io/)

```shell
$ gem install bundler
```

Clone the project

```shell
$ git clone git://github.com/berkshelf/buff-ruby_engine.git
```

and run:

```shell
$ cd buff-ruby_engine
$ bundle install
```

Bundler will install all gems and their dependencies required for testing and developing.

### Running unit (RSpec) tests

```shell
$ bundle exec guard start
```
