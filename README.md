# php_pdo_informix

Precompiled 32bit versions of the PECL extension php_pdo_informix for PHP.

Prerequisites:
* 32bit Informix CSDK installed
* INFORMIXDIR environment variable points to the CSDK install folder

Note: There's a [4 years old bug in the PECL Extension](http://bugs.php.net/bug.php?id=64008), which returns corrupted strings when character conversion is active. I patched the [the solution](https://git.php.net/?p=pecl/database/pdo_informix.git;a=commitdiff;h=a88390f3b5df685da21c40f24b0fc70740e5b56f) manually, because it's still not included in the latest release 1.3.3.
