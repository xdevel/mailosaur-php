# Mailosaur PHP Client Library

[Mailosaur](https://mailosaur.com) allows you to automate tests involving email. Allowing you to perform end-to-end automated and functional email testing.

[![Build Status](https://travis-ci.org/xdevel/mailosaur-php.svg?branch=master)](https://travis-ci.org/xdevel/mailosaur-php)

## Installation

You can install the bindings via Composer. Run the following command:

```
composer require mailosaurapp/mailosaur-php
```

To use the client library, use Composer's autoload:

```
require_once('vendor/autoload.php');
```

## Documentation and usage examples

[Mailosaur's documentation](https://mailosaur.com/docs) includes all the information and usage examples you'll need.

## Running tests

Once you've cloned this repository locally, you can simply run:

```
composer install

export MAILOSAUR_SERVER=yourserverid
export MAILOSAUR_API_KEY=yourapikey

./vendor/bin/phpunit
```

## Contacting us

You can get us at [support@mailosaur.com](mailto:support@mailosaur.com)

## License

Copyright (c) 2016 Mailosaur Ltd
Distributed under MIT license.
