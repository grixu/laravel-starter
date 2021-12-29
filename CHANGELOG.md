# Changelog

All notable changes to `laravel-starter` will be documented in this file

## 0.2.0 - 2021-12-29

- Updated Laravel to 8.77
- Added code quality tools such as: `php_cs_fixer`, `phpstan` & `php-insights`
- Added basic configuration files for that tools
- Added `xray` for checking `ray()` is not leaks to production
- Fixed minor bugs found by `phpstan`
- Added common shortcuts in `composer.json`'s `scripts` section
- Updated sail config (now using PHP 8.1 and MySQL8 with redis, meilisearch and minio.io)
- Created `.env.example.docker` as a template for `.env` file when you use `sail`

## 0.1.0 - 2021-04-27

- initial release
