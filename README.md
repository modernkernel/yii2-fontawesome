Yii2 Font Awesome
=================
Font Awesome extension for Yii2

[![Latest Stable Version](https://img.shields.io/packagist/v/powerkernel/yii2-fontawesome.svg)](https://packagist.org/packages/powerkernel/yii2-fontawesome)
[![Total Downloads](https://img.shields.io/packagist/dt/powerkernel/yii2-fontawesome.svg)](https://packagist.org/packages/powerkernel/yii2-fontawesome)
[![Build Status](https://travis-ci.org/powerkernel/yii2-fontawesome.svg?branch=master)](https://travis-ci.org/powerkernel/yii2-fontawesome)

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require powerkernel/yii2-fontawesome "~2.0"
```

or add

```
"powerkernel/yii2-fontawesome": "~2.0"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= 
    \powerkernel\fontawesome\Icon::widget([
        'prefix'=>'fas', // Optional, can be fab, fas, far or fal
        'name' => 'address-book', // icon name
        'size'=>'fa-5x', // Optional
        'styling'=>'fa-spin' // Optional
    ]) 
?>
```
For more details about how to use, see: https://fontawesome.com/how-to-use

