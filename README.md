php-skeleton
============

[![Build Status](https://travis-ci.org/adambrett/php-skeleton.png?branch=master)](https://travis-ci.org/adambrett/php-skeleton)

Use this skeleton to quickly setup and start working on a new library or application.

Installation
============

This skeleton was designed to be used with Composer. This makes setting up a new library or application quick and easy.

## Install Composer

If you have not installed Composer, do that now. I prefer to install Composer globally in `/usr/local/bin`, but you may also install Composer locally in your current working directory. For this tutorial, I assume you have installed Composer locally.

<http://getcomposer.org/doc/00-intro.md#installation>

## Install the Application

After you install Composer, run this command from the directory in which you want to install your new library or application.

    composer.phar create-project adambrett/skeleton [my-project-name]

Replace <code>[my-project-name]</code> with the desired directory name for your new application.

Basic Usage
===========

Requirements
============

  * PHP >=5.4

Contributing
============

Pull Requests
-------------

  1. Fork the php-skeleton repository
  2. Create a new branch for each feature or improvement
  3. Send a pull request from each feature branch to the **develop** branch

Style Guide
-----------

This package is compliant with [PSR-0][], [PSR-1][], and [PSR-2][]. If you
notice compliance oversights, please send a patch via pull request.

[PSR-0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[PSR-2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md

Tests
-----

The library is developed using test driven development.  All pull requests should be accompanied by passing unit tests with 100% coverage.  [phpunit][] is used for testing and [mockery][] is used for mocks.  [faker][] is available as a random data generator if required.

[phpunit]: http://phpunit.de/manual/current/en/index.html
[mockery]: https://github.com/padraic/mockery
[faker]: https://github.com/fzaninotto/Faker

Creating Builds
---------------

Some build tools are included via composer if required, you can run them using .  `./vendor/bin/phing` from the root of the project.  The output will be stored in `./build` and will include code coverage and code browser output.  Inspect the contents of `build.xml` to see what's happening underneath.

Authors
=======

Adam Brett - http://twitter.com/sixdaysad - http://adamcod.es

License
=======

php-skeleton is licensed under the BSD-3-Clause License - see the LICENSE file for details
