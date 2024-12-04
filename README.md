# Standalone Version of Laravel's Fluent Helper

![Downloads](https://img.shields.io/packagist/dt/ozankurt/fluent)
![Tests](https://img.shields.io/github/actions/workflow/status/ozankurt/fluent/tests.yml?label=tests)
[![StyleCI](https://github.styleci.io/repos/197242392/shield?style=flat&branch=master)](https://styleci.io/repos/197242392)
[![License](https://img.shields.io/github/license/ozankurt/fluent)](LICENSE.md)

### Why?

Because some contributors like to change simple and working code to a more complex and broken one just to be "contributing" to Laravel.

### Installation

Run the following command:

```bash
composer require ozankurt/fluent
```

### Usage

```php
use OzanKurt\Fluent\Fluent;

class MyObject extends Fluent {}

$object = new MyObject([
    'name' => 'Car',
    'color' => 'green',
]);

$object->speed(200)->passengers([
    ['name' => 'John Doe'],
    ['name' => 'Jane Doe'],
]);
```

## Changelog

Please see [Releases](../../releases) for more information on what has changed recently.

## Credits

- [laravel/laravel](https://github.com/laravel/laravel)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [LICENSE](LICENSE.md) for more information.
