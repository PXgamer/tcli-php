# tcli-php

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Style CI][ico-styleci]][link-styleci]
[![Code Coverage][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

A CLI torrent searching system.

## Install

Via Composer

``` bash
$ composer global require pxgamer/tcli-php
```

Via Phive

``` bash
$ phive install pxgamer/tcli-php
```

## Usage

```bash
tcli {{command}}
```

**Latest Torrents**

Command                    | Description
-------------------------- | -----------
`tcli latest`              | This will get the latest torrents from all available torrent sites.  
`tcli latest:wwt`          | This will get the latest torrents from WorldWideTorrents.  
`tcli latest:rarbg`        | This will get the latest torrents from RARBG.  
`tcli latest:eztv`         | This will get the latest torrents from EZTV.  
`tcli latest:limetorrents` | This will get the latest torrents from LimeTorrents.  

**Searching Torrents**

Command           | Description
----------------- | -----------
`tcli search`     | This will get the latest torrents from all available torrent sites.  
`tcli search:wwt` | This will get the latest torrents from WorldWideTorrents.  

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email owzie123@gmail.com instead of using the issue tracker.

## Credits

- [pxgamer][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/pxgamer/tcli-php.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/pxgamer/tcli-php/master.svg?style=flat-square
[ico-styleci]: https://styleci.io/repos/87924479/shield
[ico-code-quality]: https://img.shields.io/codecov/c/github/pxgamer/tcli-php.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/pxgamer/tcli-php.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/pxgamer/tcli-php
[link-travis]: https://travis-ci.org/pxgamer/tcli-php
[link-styleci]: https://styleci.io/repos/87924479
[link-code-quality]: https://codecov.io/gh/pxgamer/tcli-php
[link-downloads]: https://packagist.org/packages/pxgamer/tcli-php
[link-author]: https://github.com/pxgamer
[link-contributors]: ../../contributors
