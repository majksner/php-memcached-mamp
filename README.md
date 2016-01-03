# Installation:

1. Copy `memcached.so` from the appropriate subdirectory of this repo to `/Applications/MAMP/bin/php/php5.x.x/lib/php/extensions/no-debug-non-zts-200xxxxx` (Channge 5.x.x to your PHP version)
2. Add `extension=memcached.so` to the end of `php.ini` (Open MAMP click on File → Edit Template → PHP → PHP 5.x.x php.ini), for non-pro users edit `/Applications/MAMP/bin/php/php5.x.x/conf/php.ini` (Channge 5.x.x to your PHP version)
3. Restart MAMP.

## Dependencies:
1. `$ brew install memcached`
2. `$ brew install libmemcached`

### Change Log:
* 0.14 (01/02/2015) PHP-PECL-MEMCACHED 2.2.0 update for PHP 7.0.0 and it works with latest MAMP 3.5
* 0.12 (06/28/2015) PHP-PECL-MEMCACHED 2.2.0 update for PHP 5.6.10, PHP 5.5.26 and it works with latest MAMP 3.3
* 0.11 (12/06/2014) PHP-PECL-MEMCACHED 2.2.0 updated for PHP 5.6.2 PHP 5.5.18, 5.4.34 and 5.3.29 it works with latest MAMP 3.0.7.3
* 0.10 (09/12/2014) PHP-PECL-MEMCACHED 2.2.0 updated for PHP 5.5.14, 5.4.30 and 5.3.28 it works with latest MAMP 3.0.6
* 0.9 (04/12/20014) PHP-PECL-MEMCACHED 2.2.0 updated for PHP 5.5.10, 5.4.26 and 5.3.28 it works with latest MAMP 3.0.4
* 0.8 (03/06/20014) PHP-PECL-MEMCACHED updated for PHP 5.5.10 it works with latest MAMP 3.0.2
* 0.8 (03/06/20014) PHP-PECL-MEMCACHED updated for new PHP 5.3.28, 5.4.25 and 5.5.9 it works with latest MAMP 3.0.1
* 0.7 (09/29/2013) PHP-PECL-MEMCACHED updated for new PHP 5.3.27, 5.4.19 and 5.5.3 it works with latest MAMP 2.2
* 0.6 (03/13/2013) PHP-PECL-MEMCACHED updated for PHP 5.3.20, it works with latest MAMP 2.1.2
* 0.5 (03/12/2013) PHP-PECL-MEMCACHED updated for PHP 5.4.10, it works with latest MAMP 2.1.2
* 0.4 (09/07/2012) PHP-PECL-MEMCACHED updated for PHP 5.4.4, it works with MAMP 2.1.1
* 0.3 (08/08/2012) PHP-PECL-MEMCACHED updated to the version (2.1.0), it works with the MAMP 2.1.x and PHP 5.3.14.
* 0.2 (05/14/2012) PHP-PECL-MEMCACHED updated to the version (2.0.1), it works with the MAMP 2.0.5
* 0.1 - Initial Release
