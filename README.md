[![](https://github.com/ansible-roles-matsumura/jq/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3Abuild)

Role Description
=========

Installs [jq](https://stedolan.github.io/jq/) for CentOS7/CentOS8.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

EPEL installed before running this role.

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - robertdebock.epel
    - jq
```

License
-------

BSD
