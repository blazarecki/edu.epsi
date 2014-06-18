# EPSI TD

## Requirements

- [Vagrant](http://www.vagrantup.com)
- [Virtualbox](https://www.virtualbox.org/wiki/Downloads)

## Install

- `git clone git@github.com:blazarecki/edu.epsi.git`
- `vagrant up`
- `vagrant ssh`
- `$ cd /var/www`
- `php composer.phar install`

Add the following to your hosts file : `192.168.56.101 epsi.dev`

You can now access to the projet via [http://epsi.dev/](http://epsi.dev)
