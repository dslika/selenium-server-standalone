# selenium-server-standalone

![Travis CI](https://travis-ci.org/sveneisenschmidt/selenium-server-standalone.svg?branch=master) [![Latest Stable Version](https://poser.pugx.org/se/selenium-server-standalone/v/stable)](https://packagist.org/packages/se/selenium-server-standalone) [![Total Downloads](https://poser.pugx.org/se/selenium-server-standalone/downloads)](https://packagist.org/packages/se/selenium-server-standalone) [![Latest Unstable Version](https://poser.pugx.org/se/selenium-server-standalone/v/unstable)](https://packagist.org/packages/se/selenium-server-standalone) [![License](https://poser.pugx.org/se/selenium-server-standalone/license)](https://packagist.org/packages/se/selenium-server-standalone)


Composer distribution of Selenium Server Standalone, the browser automation framework.

## Installation

#### Inside your composer-powered project
```bash
composer require dslika/selenium-server-standalone
```

#### Standalone

```bash
composer install
```

The command `composer install` will make the selenium executable from inside `bin`.

## Usage

```bash
$ bin/selenium-server-standalone
```

Arguments are supported.

```bash
$ bin/selenium-server-standalone -port 4445
```
