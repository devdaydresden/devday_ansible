devday.wordpress
================

Setup a Wordpress instance for Dev Day.

Requirements
------------

This role expects a database that can be used for Wordpress which can be setup using
[the devday.mariadb role](../devday.mariadb). 

Role Variables
--------------

- `devday_wordpress_db_password` defines the password of the wordpress database user
- `devday_wordpress_version` defines the version of the wordpress docker image

Dependencies
------------

- `community.docker`

Example Playbook
----------------

```
- hosts: servers
  roles:
    - devday.wordpress
```

License
-------

GPLv3 or later

Author Information
------------------

This module is part of the Dev Day event website.

- [Project page](https://github.com/devdaydresden/devday_ansible)
