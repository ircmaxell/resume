# Major Project Participation

## 2007 - 2009: Joomla

I was a core developer of the [Joomla! CMS](https://www.joomla.com). I head up the release and support teams as well as the security team (including creating a security process from scratch).

## 2012 - 2016: PHP

Core contributor to the [PHP Programming Language](https://www.php.net) driving language features from the PHP 5.5 release through PHP 7. Primarially led two well-known features:

 * [Password Hash Functionality](https://wiki.php.net/rfc/password_hash) - adding the `password_hash()` family of functions for simplified password storage
 * [Scalar Type Declarations](https://wiki.php.net/rfc/scalar_type_hints_v5) - Adding support in PHP 7+ for scalar types

Additionally, I was involved in the creation of a large number of other RFCs in an advisory or consultory manner. 

# Notable Projects

## password_compat

The [`password_compat`](https://github.com/ircmaxell/password_compat) project polyfills the Password Hash functionality added to PHP 5.5 back to lower version (PHP 5.3 and 5.4 specifically).

## RandomLib

[RandomLib](https://github.com/ircmaxell/RandomLib) made generating cryptographically secure random numbers in PHP easy. Since PHP 7 introduced the `random_int()` family of functions, the project is no longer needed.

# Compiler Projects

## PHPPHP

[PHPPHP](https://github.com/ircmaxell/PHPPHP) implemented PHP's engine in PHP itself. It did not aim to be production worthy, but instead focused on education.

## Recki-CT

[Recki-CT](https://github.com/google/recki-ct) was an initial attempt at building an Ahead of Time Compiler for PHP. It used a pluggable backend system to generate machine code.

## PHP-Compiler

[PHP-Compiler](https://github.com/ircmaxell/php-compiler/) is a new attempt at an Ahead of Time Compiler for PHP, based around PHP 7.4's FFI system and LLVM.

# Other Projects

[Github](https://github.com/ircmaxell?tab=repositories) and [Packagist](https://packagist.org/packages/ircmaxell/) detail open source contributions and PHP packages that I built and shipped.

# Other Contributions

**Discovered** and **reported** security vulnerabilities and bugs in several projects including WordPress, Joomla, Drupal, Zend Framework, Cake Framework, Kohana Framework, Symfony Framework, Doctrine ORM, PHP, IIS and several other platforms.