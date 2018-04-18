# CHANGELOG

## 1.11.1
* Fix Codacy warnings (@ajardin)
* Code reformat (@ajardin)
* Remove version from the module name (@ajardin)

## 1.11.0
* Update README (@ajardin)
* Drop support of previous Apache versions (@ajardin)
* Replace HTTP_FORBIDDEN by HTTP_TOO_MANY_REQUESTS (@ajardin)
* Add the possibility to use XFF HTTP request header (@ajardin)
* Add support for Apache 2.4 (@ajardin)

## 1.10.1
* Fixed IP Whitelisting in Apache 1.3 Version (@jzdziarski)
* Corrected initialization to prevent dumping IP database (@jzdziarski)
* Documentation and code cleaned up, renamed mod_evasive (@jzdziarski)

## 1.10.0
* Security fix: Tempdir configuration directive (race condition) (@jzdziarski)

## 1.9.0
* Added NSAPI/SunONE Support (@jzdziarski)
* Added TEMP_HOME definition to change temporary file locations (@jzdziarski)

## 1.8.0
* Added support for IP Whitelisting (@jzdziarski)

## 1.7.1
* Minor bugfixes to Apache 2.0 module (@jzdziarski)
* Corrections to object creation and cleanup (@jzdziarski)

## 1.7.0
* Support for Apache 2.0 (@jzdziarski)

## 1.6.1
* Bugfix: free() of another static variable (@jzdziarski)
 
## 1.6.0
* Added syslog support (@jzdziarski)

## 1.5.1
* Bugfix: free() of a static variable (@jzdziarski)

## 1.5.0
* Added automated email notification (@jzdziarski)
* Added configurable system command (@jzdziarski)

## 1.4.0
* Added support fror httpd.conf directives (@jzdziarski)
* Added --add-module support (@jzdziarski)

## 1.0.0
* Initial Release (@jzdziarski)
