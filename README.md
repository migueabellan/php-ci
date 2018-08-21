# PHP-CI

> Simple example in PHP to test **Continuous Integration** in different platforms

TravisCI

[![Travis CI](https://travis-ci.org/migueabellan/php-ci.svg?branch=master)](https://travis-ci.org/migueabellan/php-ci)

CircleCI

[![CircleCI](https://circleci.com/gh/migueabellan/php-ci/tree/master.svg?style=svg)](https://circleci.com/gh/migueabellan/php-ci/tree/master)

Gitlab Pipeline

[![GitlabCI](https://gitlab.com/migueabellan/php-ci/badges/master/pipeline.svg)](https://gitlab.com/migueabellan/php-ci/commits/master)

Bitbucket Pipeline

[![BitbucketCI](https://img.shields.io/bitbucket/pipelines/migueabellan/php-ci.svg)](https://bitbucket.org/migueabellan/php-ci/addon/pipelines/home#!/)


### Requirements

```sh
$ php --version
PHP >= 7.0
$ composer --version
composer >= 1.6
$ phpunit --version
PHPUnit >= 6.5
```



### Installing

Clone this repository

```sh
$ git clone https://github.com/migueabellan/php-ci.git

or 

$ git clone https://gitlab.com/migueabellan/php-ci.git

or

$ git clone https://bitbucket.org/migueabellan/php-ci.git
```

Install with composer

```sh
$ composer install
```

Test

```sh
$ phpunit tests/MyTest.php
```