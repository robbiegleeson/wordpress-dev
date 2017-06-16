# Wordpress Vagrant Development Environment


# What's Installed

+ Ubuntu Trusty (14.04)
+ Wordpress
+ Mysql
+ Php
+ Phpmyadmin
+ Subversion
+ Git
+ Composer
+ Xdebug
+ PHPUnit - **installed via composer*
+ phploc - **installed via composer*
+ phpcpd - **installed via composer*
+ phpdcd - **installed via composer*
+ phpcs - **installed via composer*
+ phpdepend - **installed via composer*
+ phpmd - **installed via composer*
+ PHP_CodeBrowser - **installed via composer*
+ WordPress sniffs for phpcs
+ WordPress Unit Tests - **installed via composer*

# Prerequisites

+ [Vagrant](http://www.vagrantup.com/downloads.html)
+ [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
+ [Vagrant Hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater)

## Getting Started

This is a fairly simple project to get up and running.  
The procedure for starting up a working WordPress is as follows:

1. Clone the project.  (There’s only master branch.)
2. Run `vagrant plugin install vagrant-hostsupdater` from command line
2. Run the command `vagrant up` from the directory
3. Open your browser to http://vagrantpress.dev

## Working with the environment

To log in to the local Wordpress installation:

`http://vagrantpress.dev/wp-admin/` the username is `admin`, the password is `vagrant`.

You can access phpMyAdmin:

`http://vagrantpress.dev/phpmyadmin/` with username `wordpress`, password `wordpress`.

## A Few Details

* If you're needing a password (for anything - including mysql, it should be `vagrant`)

## Get your theme!

Now you're Wordpress install is up and running it's time to roll your own theme. Head over to [Underscores.me] (http://underscores.me/), enter in your theme name and hit Generate.

Drop the theme into the themes directory (wordpress/wp-content/themes) and unzip it!

Go to your wp-admin and set your theme and that's it- get coding (ugh and styling!)
