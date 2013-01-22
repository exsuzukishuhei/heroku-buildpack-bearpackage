BEAR.Package build pack for Heroku
========================


Configuration
-------------

The config files are bundled with the buildpack itself:

* conf/httpd.conf
* conf/php.ini

Configure Heroku to use this buildpack repo AND branch

    heroku create -s cedar -b https://github.com/exsuzukishuhei/heroku-buildpack-bearpackage.git
    OR
    heroku config:set BUILDPACK_URL=https://github.com/exsuzukishuhei/heroku-buildpack-bearpackage.git


