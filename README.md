HTML5 Shiv asset for Yii2 framework
===============================

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist ezoterik/yii2-html5shiv-asset "*"
```

or add

```
"ezoterik/yii2-html5shiv-asset": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Register Html5ShivAsset in your *views* with:
 ```php
 ezoterik\html5shivAsset\Html5ShivAsset::register($this);
 ```

Or set a dependancy in your AppAsset with:
 ```php
 public $depends = [
     // ...
     'ezoterik\html5ShivAsset\Html5ShivAsset',
     // ...
 ];
 ```