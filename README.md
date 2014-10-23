Sylius Standard Edition
=======================

Sylius is an open source e-commerce solution for **PHP**, based on the [**Symfony2**](http://symfony.com) framework.

This package contains the Sylius Standard Edition, which serves as a foundation for your custom apps.

Installation
------------

Clone the forked repository.
``` bash
$ git clone git@github.com:astina-forks/Sylius-Standard.git
```

Start vagrant, then ssh into the box and install:
``` bash
$ composer install
$ php app/console sylius:install
```

Configure Git
-------------

Sylius bundles in `vendor/sylius/sylius` are from the [astina-forks/Sylius](https://github.com/astina-forks/Sylius) repository, composer installs them from GitHub. 
In order to be able to merge upstream code, add the upstream remote.
``` bash
$ cd vendor/sylius/sylius
$ git remote add upstream git://github.com/Sylius/Sylius.git 
```

There are now 3 remotes in this directory, **do not remove the one named** `composer`.


Contributing
------------

All informations about contributing to Sylius can be found on [this page](http://docs.sylius.org/en/latest/contributing/index.html).

Sylius on twitter
-----------------

If you want to keep up with the updates, [follow the official Sylius account on twitter](http://twitter.com/Sylius).

MIT License
-----------

License can be found [here](https://github.com/Sylius/Sylius/blob/master/LICENSE).

Authors
-------

Sylius was originally created by [Paweł Jędrzejewski](http://pjedrzejewski.com).
See the list of [contributors](https://github.com/Sylius/Sylius/contributors).
