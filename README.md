almaops.ct_keycloak
==========

This ansible role installs a set of docker containers for keycloak cluster.

Requirements
------------

Role: [almaops.docker](https://galaxy.ansible.com/almaops/docker)

Role Variables
--------------

Look into [./defaults/main.yml](./defaults/main.yml)

Example Playbook
----------------

```
- hosts: servers
  roles:
    - role: almaops.ct_keycloak
```

License
-------

[MIT License](./LICENSE)


Author Information
------------------
Dmitrii Kashin, <freehck@freehck.com>
