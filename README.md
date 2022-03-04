[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/jq/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/jq/tree/main)

Role Description
=========

Installs [jq](https://stedolan.github.io/jq/) for CentOS7/Stream8.

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
