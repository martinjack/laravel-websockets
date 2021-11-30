# Laravel WebSockets 🛰

[![Latest Stable Version](http://poser.pugx.org/jackmartin/laravel-websockets/v)](https://packagist.org/packages/jackmartin/laravel-websockets) [![Total Downloads](http://poser.pugx.org/jackmartin/laravel-websockets/downloads)](https://packagist.org/packages/jackmartin/laravel-websockets)

Bring the power of WebSockets to your Laravel application. Drop-in Pusher replacement, SSL support, Laravel Echo support and a debug dashboard are just some of its features.

[![https://phppackagedevelopment.com](https://beyondco.de/courses/phppd.jpg)](https://phppackagedevelopment.com)

If you want to learn how to create reusable PHP packages yourself, take a look at my upcoming [PHP Package Development](https://phppackagedevelopment.com) video course.

# Composer
```shell
composer require jackmartin/laravel-websockets
```

## Service provider
```shell
php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="migrations"
```
```shell
php artisan migrate
```

## WebSocket configuration
```shell
php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="config"
```


## Documentation

For installation instructions, in-depth usage and deployment details, please take a look at the [official documentation](https://docs.beyondco.de/laravel-websockets/).

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email marcel@beyondco.de instead of using the issue tracker.

## Credits

- [Marcel Pociot](https://github.com/mpociot)
- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
