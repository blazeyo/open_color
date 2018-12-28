# Open Color

A simple PHP utility class with the [Open Color](https://yeun.github.io/open-color/) palette.

## Installation

```shell
composer require blazeyo/open_color
```

## Usage

```php
use OpenColor\Colors;

$openColor = Colors::getColors();
// ['gray' => ['#f8f9fa', '#f1f3f5', ...], 'red' => ... ]
```
