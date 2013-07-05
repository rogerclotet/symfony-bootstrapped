Symfony Bootstrapped Edition
============================

Modified version of the Symfony 2.3.1 Standard edition with a few changes and initialisation,
mostly Twitter Bootstrap and less css.

Installing the Symfony Bootstrapped Edition
-------------------------------------------

As in the Standard Edition, you have two main options to install the Bootstrapped
Edition:

### Use Composer (*recommended*)

As Symfony uses [Composer][1] to manage its dependencies, the recommended way
to create a new project is to use it.

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

    curl -s http://getcomposer.org/installer | php

Then, use the `create-project` command to generate a new Symfony application:

    php composer.phar create-project rogerclotet/symfony-bootstrapped path/to/install

Composer will install Symfony and all its dependencies under the
`path/to/install` directory.

### Download an Archive File

To quickly test Symfony, you can also download an [archive][2] of the Bootstrapped
Edition and unpack it somewhere under your web server root directory.

If you downloaded an archive "without vendors", you also need to install all
the necessary dependencies. Download composer (see above) and run the
following command:

    php composer.phar install

[1]:  http://getcomposer.org/
[2]:  https://github.com/rogerclotet/symfony-bootstrapped-edition/archive/master.zip
