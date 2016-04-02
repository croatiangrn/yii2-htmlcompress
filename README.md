# yii2-htmlcompress [![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE) [![Scrutinizer](https://img.shields.io/scrutinizer/g/croatiangrn/yii2-htmlcompress.svg?style=flat-square)](https://scrutinizer-ci.com/g/croatiangrn/yii2-htmlcompress/)

Compress HTML output into a single line

## Install

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

try

```
composer require "croatiangrn/yii2-htmlcompress:*"
```

or add

```
"croatiangrn/yii2-htmlcompress": "*"
```

to the require section of your `composer.json` file.

## Configure

```
return [
    // ...
    'components' => [
        // ...
        'view' => [
            'class' => '\croatiangrn\htmlcompress\View',
            'compress' => YII_ENV_DEV ? false : true,
            // ...
        ]
    ]
];
```

By default extension is disabled on DEV environment and enabled on PROD.

Enjoy ;)
