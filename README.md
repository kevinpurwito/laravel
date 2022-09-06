# About Laravel

[![Tests](https://github.com/kevinpurwito/laravel/actions/workflows/run-tests.yml/badge.svg?branch=main)](https://github.com/kevinpurwito/laravel/actions/workflows/run-tests.yml)
[![Pint CS](https://github.com/kevinpurwito/laravel/actions/workflows/pint-cs.yml/badge.svg?branch=main)](https://github.com/kevinpurwito/laravel/actions/workflows/pint-cs.yml)
[![PHPStan](https://github.com/kevinpurwito/laravel/actions/workflows/phpstan.yml/badge.svg?branch=main)](https://github.com/kevinpurwito/laravel/actions/workflows/phpstan.yml)

Laravel is a PHP framework.

We believe development must be an enjoyable and creative experience to be truly fulfilling.

## Created with

- **[Laravel](https://laravel.com/)**

## Installation

``` bash
composer create-project kevinpurwito/laravel app-name
composer install
cp .env.example .env

php artisan vendor:publish --provider "OwenIt\Auditing\AuditingServiceProvider" --tag="migrations"
php artisan vendor:publish --provider="Spatie\MediaLibrary\MediaLibraryServiceProvider" --tag="migrations"
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"

php artisan migrate --seed
php artisan key:generate
```

## Testing
``` bash
php artisan test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Security Vulnerabilities

If you discover any security-related issues, please email [kevin.purwito@gmail.com](mailto:kevin.purwito@gmail.com)
instead of using the issue tracker. All security vulnerabilities will be promptly addressed.
