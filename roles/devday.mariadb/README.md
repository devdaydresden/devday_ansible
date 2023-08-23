devday.mariadb
==============

Setup MariaDB database container for Dev Day applications that are not usable with PostgreSQL.

Requirements
------------

None

Role Variables
--------------

- `devday_mariadb_root_password` defines the password of the MariaDB admin user
- `devday_mariadb_version` defines the version of the mariadb Docker image that should be used
- `devday_wordpress_db_password` defines the password of the wordpress database user

Dependencies
------------

- `community.docker`

Example Playbook
----------------

```
- hosts: servers
  roles:
    - devday.mariadb
```

License
-------

GPLv3 or later

Author Information
------------------

This module is part of the Dev Day event website.

- [Project page](https://github.com/devdaydresden/devday_ansible)
