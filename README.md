# Kanekes

Kanekes is one of laravel base theme for bantenprov application.

## Release

| Release  | Description             |
|----------|-------------------------|
| 0.1.0    | development alpha stage |
| dev      | development alpha stage |
| master   | master branch           |

## How to install

```
$ composer create-project bantenprov/kanekes "dev-dev"
```

### Update config/app.php

```php
// config/app.php

'providers' => [
    '...',
    Eusonlito\LaravelMeta\MetaServiceProvider::class,
];

'aliases' => [
    '...',
    'Meta'    => Eusonlito\LaravelMeta\Facade::class,
];
```

### publish the package's assets to public folder

```php
$ php artisan vendor:publish --provider="Eusonlito\LaravelMeta\MetaServiceProvider"
```

## Feature:

- Materialize CSS [dogfalo/materialize](https://github.com/dogfalo/materialize/).
- Metatag from [eusonlito/laravel-Meta](https://github.com/eusonlito/laravel-Meta).
- Schema.org from [spatie/schema-org](https://github.com/spatie/schema-org).
