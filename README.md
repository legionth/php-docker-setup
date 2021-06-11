# PHP, Nginx, Mysql & Node for your development environment

Containers for your development with PHP.

**Table of contents**

* [Node is also installed](#node-is-also-installed)
* [Speed up for Mac](#speed-up-for-mac)
* [License](#license)


## What is the purpose of this repository?

I created this repository to try out some [Symfony](https://symfony.com/)
projects in combination with [TailwindCSS](https://tailwindcss.com/).

It's a container enviroment that should cover most of my personal 
development process.

## Node is also installed

Node & NPM is installed in the Nginx containe, so you can install your finest
NPM packages.


## Speed up for Mac

If you look closely in [docker-compose.yml](docker-compose.yml), you will find `:delegated`
behind the paths.

This helps to speed up the mounting from the container to the host.

If you use another system than Mac, you should be fine.

## License

MIT, see [LICENSE file](LICENSE).
