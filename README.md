# PHP SDK for MarketData.app

[![Latest Version on Packagist](https://img.shields.io/packagist/v/kerryjones/marketdataapp-sdk-php.svg?style=flat-square)](https://packagist.org/packages/kerryjones/marketdataapp-sdk-php)
[![Tests](https://img.shields.io/github/actions/workflow/status/kerryjones/marketdataapp-sdk-php/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/kerryjones/marketdataapp-sdk-php/actions/workflows/run-tests.yml)
[![Codecov](https://codecov.io/gh/KerryJones/marketdataapp-sdk-php/graph/badge.svg?token=5W2IB9F6RU)](https://codecov.io/github/KerryJones/marketdataapp-sdk-php)
[![Total Downloads](https://img.shields.io/packagist/dt/kerryjones/marketdataapp-sdk-php.svg?style=flat-square)](https://packagist.org/packages/kerryjones/marketdataapp-sdk-php)

This is an unofficial PHP SDK for Market Data. It provides developers with a powerful, easy-to-use interface to obtain
real-time and historical financial data. Ideal for building financial applications, trading bots, and investment
strategies.

## Installation

You can install the package via composer:

```bash
composer require kerryjones/marketdataapp-sdk-php
```

## Usage

```php
$client = new MarketDataApp\Client();
$quote = $client->indices->quote('AAPL');
```

## Testing

```bash
./vendor/bin/phpunit tests
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Credits

- [KerryJones](https://github.com/KerryJones)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
