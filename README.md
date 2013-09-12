CsnIveTheme
===========
Zend Framework 2 Module

###What is CsnIveTheme?###

CsnIveTheme is a theme for your modules.

Installation
------------
1. Installation via composer is supported, simply run: `php composer.phar require coolcsn/csn-ive-theme:dev-master`. The installed module is located in *./vendor/coolcsn/csn-ive-theme*.

2. Add `CsnIveTheme`, `DoctrineModule` and `DoctrineORMModule` in your application configuration at: `./config/application.config.php`. An example configuration may look like the following :

```
'modules' => array(
    'Application',
    'DoctrineModule',
    'DoctrineORMModule',
    'CsnIveTheme'
)
```

Configuration
-------------
Change directory of the file `loader.php` from `./vendor/coolcsn/csn-ive-theme/loader.php` to `./public/loader.php`. This php file is the connection between *./vendor/coolcsn/csn-ive-theme/view/layout/index.phtml* and *./vendor/coolcsn/csn-ive-theme/assets*. In folder *assets* are located **.css, *.png/*.jpg and *.js* files.

Dependencies
------------

This Module depends on the following Modules:

 - [Zend Framework 2](https://github.com/zendframework/zf2) 

 - [DoctrineORMModule] (https://github.com/doctrine/DoctrineORMModule) - DoctrineORMModule integrates Doctrine 2 ORM with Zend Framework 2 quickly and easily.

Recommends
----------
- [coolcsn/CsnUser](https://github.com/coolcsn/CsnUser) - Module for Authentication;

- [coolcsn/CsnAuthorization](https://github.com/coolcsn/CsnAuthorization) - Module for Authorization;
 
- [coolcsn/CsnNavigation](https://github.com/coolcsn/CsnNavigation) - Navigation module;
 
- [coolcsn/CsnCms](https://github.com/coolcsn/CsnCms) - Content management system;
