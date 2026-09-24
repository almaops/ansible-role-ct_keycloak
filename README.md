# DEPRECATION NOTICE
This repo is archived and no longer maintained.  
`ct_keycloak` role is provided via [almaops.common](https://github.com/almaops/ansible-collection-common/tree/master/roles/ct_keycloak) collection.

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
