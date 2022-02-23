# Enable Ray in all PHP files on your system

[![Latest Version on Packagist](https://img.shields.io/packagist/v/spatie/global-ray.svg?style=flat-square)](https://packagist.org/packages/spatie/global-ray)
[![Tests](https://github.com/spatie/global-ray/actions/workflows/run-tests.yml/badge.svg?branch=main)](https://github.com/spatie/global-ray/actions/workflows/run-tests.yml)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/global-ray.svg?style=flat-square)](https://packagist.org/packages/spatie/global-ray)

By installing Ray globally, you can use `ray()` and [all framework agnostic Ray functions](https://spatie.be/docs/ray/v1/usage/framework-agnostic-php-project) in any PHP app or script on your system.

## Support us

[<img src="https://github-ads.s3.eu-central-1.amazonaws.com/global-ray.jpg?t=1" width="419px" />](https://spatie.be/github-ad-click/global-ray)

We invest a lot of resources into creating [best in class open source packages](https://spatie.be/open-source). You can support us by [buying one of our paid products](https://spatie.be/open-source/support-us).

We highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using. You'll find our address on [our contact page](https://spatie.be/about-us). We publish all received postcards on [our virtual postcard wall](https://spatie.be/open-source/postcards).

## Installation

You can install the global Ray via composer:

```bash
composer global require spatie/global-ray
ray install
```

When running `ray install`, we'll add a line in your `php.ini` to automatically load ray, allowing ray to be available in any PHP project or script.

## Usage

You can use `ray()` and [all Ray's framework agnostic functions](https://spatie.be/docs/ray/v1/usage/framework-agnostic-php-project) in any PHP file.

### Using framework specific functionality

To use framework specific functionality, such as [viewing queries in Laravel](https://spatie.be/docs/ray/v1/usage/laravel#showing-queries), or [displaying mails in WordPress](https://spatie.be/docs/ray/v1/usage/wordpress#displaying-mails), you should still [install the relevant package or library](https://spatie.be/docs/ray/v1/installation-in-your-project/introduction).

If a framework specific package is detected, it will be used instead of the global Ray.

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Steve Bauman](https://github.com/stevebauman)
- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
