devday.pretalx
==============

Setup [PreTalx](https://github.com/pretalx/pretalx) for Dev Day.

Requirements
------------

None

Role Variables
--------------

- `devday_pretalx_db_password` defines the password of the pretalx database user

Dependencies
------------

- `community.docker`

Example Playbook
----------------

```
- hosts: servers
  roles:
    - devday.pretalx
```

License
-------

GPLv3 or later

Author Information
------------------

This module is part of the Dev Day event website.

- [Project page](https://github.com/devdaydresden/devday_ansible)
