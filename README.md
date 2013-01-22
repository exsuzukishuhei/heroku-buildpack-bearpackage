Apache + PHP 5.4 + BEAR.Package build pack
========================


Configuration
-------------

The config files are bundled with the buildpack itself:

* conf/httpd.conf
* conf/php.ini

Configure Heroku to use this buildpack repo AND branch

    heroku config:set BUILDPACK_URL=https://shuheisuzuki@bitbucket.org/shuheisuzuki/heroku-buildpack-bearpackage.git


