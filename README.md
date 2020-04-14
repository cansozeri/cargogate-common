# CargoGate Common
**Core components for the CargoGate PHP cargo processing library**

CargoGate is a framework agnostic, multi-gateway cargo processing library for PHP. This package implements common classes required by CargoGate.

# Http Library
If a library depends on HTTPlug, it requires the virtual package php-http/client-implementation. A virtual package is used to declare that the library needs an implementation of the HTTPlug interfaces, but does not care which implementation specifically.

When using such a library, you need to choose a HTTPlug client and include that in your project explicitly.

You have to use one of these packages for PHP-HTTP message factory!!

* guzzlehttp/psr7
* slim/slim
* laminas/laminas-diactoros

You have to use one of these packages for PHP-HTTP client Factory!!

* php-http/curl-client
* php-http/guzzle6-adapter

For details : [HTTPlug for library users](http://docs.php-http.org/en/latest/httplug/users.html)
