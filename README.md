# Laravel 8 model factories for Laravel 7

[![Latest Version on Packagist](https://img.shields.io/packagist/v/soyhuce/laravel-8-factories.svg?style=flat-square)](https://packagist.org/packages/soyhuce/laravel-8-factories)
[![Total Downloads](https://img.shields.io/packagist/dt/soyhuce/laravel-8-factories.svg?style=flat-square)](https://packagist.org/packages/soyhuce/laravel-8-factories)

This package is an extraction of class-based Laravel 8 model factories in order to use them in Laravel 7.

## Installation

You should install this package using composer :
```shell script
composer require --dev soyhuce/laravel-8-factories
```
Then, publish factory stub
```shell script
mkdir -p stubs
cp vendor/soyhuce/laravel-8-factories/assets/factory.stub stubs/factory.stub
``` 
Add in your `composer.json` autoload-dev psr-4 configuration 
```json
"autoload-dev": {
    "psr-4": {
        "Database\\Factories\\": "database/factories"
    }
},
```

## Documentation

There is not documentation yet but feel free to contribute in [laravel/doc](https://github.com/laravel/docs) repository.

## Bugs

The only goal of this project is being able to use Laravel 8 model factories. If it has some bugs, please report them in [laravel/framework](https://github.com/laravel/framework). 

## Contributing

You can contribute on model factories directly on [laravel/framework](https://github.com/laravel/framework). 

If this package needs to be updated, feel free to PR. A `composer update-sources` command is available for this.
