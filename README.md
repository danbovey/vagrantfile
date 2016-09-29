# vagrantfile

My Vagrant development box for LEMP projects

- ubuntu/trusty64
- nginx
- PHP 7
- MariaDB 10.1
- composer
- phpMyAdmin

## Install

Edit the `host` variable at the top of the Vagrant config then start!

```
$ vagrant up
```

- Site URL: http://`host`
- phpMyAdmin: http://`host`/phpmyadmin