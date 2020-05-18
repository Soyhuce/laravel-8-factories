# Laravel 8 factories for Laravel 7

This package is an extraction of class-based Laravel 8 factories in order to use them in Laravel 7.

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
