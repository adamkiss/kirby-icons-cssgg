# Kirby Icons: CSS.gg

[css.gg](https://css.gg/app) icons, packaged as snippets with the inline svg code for the [Kirby CMS](https://getkirby.com/).

## Installation

Either download the folder and copy it to your `site/plugins/` folder, or with composer:
``` bash
composer require adamkiss/kirby-icons-cssgg
```

## Usage

``` php
// use an icon as is
snippet('icons/check');

// or add additional classes
snippet('icons/check', ['class' => 'red-color']);
```