# (WIP) Symfony-Jelastic

The JPS package deploys a Symfony infrastructure that initially contains 1 application server (Apache2, PHP 8.1), 1 MySQL 5.7 database container and 1 load balancing server (NGINX).

## How to use ?

* Import this manifest in your Jelastic: **https://raw.githubusercontent.com/yoanbernabeu/Symfony-Jelastic/main/manifest.jps**
* Delete the example directories: **/var/www/public** and **/var/www/html**
* Clone and install your project in /var/www
* Have fun !
