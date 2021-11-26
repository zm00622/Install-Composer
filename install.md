https://getcomposer.org/basic-usage

# Locally Install Composer

To install Composer locally, run the installer in your project directory. See the Download page for instructions.

The installer will check a few PHP settings and then download composer.phar to your working directory. This file is the Composer binary. It is a PHAR (PHP archive), which is an archive format for PHP which can be run on the command line, amongst other things.

Now run php composer.phar in order to run Composer.

You can install Composer to a specific directory by using the --install-dir option and additionally (re)name it as well using the --filename option. When running the installer when following the Download page instructions add the following parameters:

php composer-setup.php --install-dir=bin --filename=composer
Now run php bin/composer in order to run Composer.

# Locally Install Laravel

https://laravel.com/docs/8.x/installation#getting-started-on-macos
