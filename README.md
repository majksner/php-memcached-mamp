# Installation:

1. Copy memcached.so from the appropriate subdirectory of this repo to /Applications/MAMP/bin/php/php5.x.x/lib/php/extensions/no-debug-non-zts-200xxxxx (Channge 5.x.x to your PHP version)
2. Add extension="memcached.so" to the end of php.ini (Open MAMP click on File → Edit Template → PHP → PHP 5.x.x php.ini), for non-pro users edit /Applications/MAMP/bin/php/php5.x.x/conf/php.ini (Channge 5.x.x to your PHP version)
3. Restart MAMP.

## Dependencies:
1. memcached (brew install memcached)
2. libmemcached (brew install libmemcached)

### Change Log:
* 0.7 (09/29/2013) PHP-PECL-MEMCACHED updated for new PHP 5.3.27, 5.4.19 and 5.5.3 it works with latest MAMP 2.2
* 0.6 (03/13/2013) PHP-PECL-MEMCACHED updated for PHP 5.3.20, it works with latest MAMP 2.1.2
* 0.5 (03/12/2013) PHP-PECL-MEMCACHED updated for PHP 5.4.10, it works with latest MAMP 2.1.2
* 0.4 (09/07/2012) PHP-PECL-MEMCACHED updated for PHP 5.4.4, it works with MAMP 2.1.1
* 0.3 (08/08/2012) PHP-PECL-MEMCACHED updated to the version (2.1.0), it works with the MAMP 2.1.x and PHP 5.3.14.
* 0.2 (05/14/2012) PHP-PECL-MEMCACHED updated to the version (2.0.1), it works with the MAMP 2.0.5
* 0.1 - Initial Release
