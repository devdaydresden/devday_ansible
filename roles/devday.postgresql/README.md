devday.postgresql
=================

Setup PostgreSQL database container for Dev Day applications.

Requirements
------------

None

Role Variables
--------------

- `devday_postgres_password` defines the password of the postgres user
- `devday_postgres_version` defines the version of the postgres Docker image that should be used
- `devday_pretalx_db_password` defines the password of the pretalx database user

Dependencies
------------

- `community.docker`

Example Playbook
----------------

```
- hosts: servers
  roles:
    - devday.postgresql
```

License
-------

GPLv3 or later

Author Information
------------------

This module is part of the Dev Day event website.

- [Project page](https://github.com/devdaydresden/devday_ansible)
