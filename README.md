Yii2 Postgresql Admin
=====================
An administration tool for Postgresql

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist johnsnook/yii2-pgsql-admin "*"
```

or add

```
"johnsnook/yii2-pgsql-admin": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \johnsnook\pgsqlAdmin\AutoloadExample::widget(); ?>```