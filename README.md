# PHP, Nginx, Mysql & Node for your development environment

Containers for your development with PHP.


## Node is also installed

Node & NPM is installed in the Nginx containe, so you can install your finest
NPM packages.


## Speed up for Mac

If you look closely in `docker-compose.yml`, you will find `:delegated`
behind the paths.

This helps to speed up the mounting from the container to the host.

If you use another system than Mac, you should be fine.



