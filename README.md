[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/jq/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/jq/tree/main)

Role Description
=========

Installs [jq](https://stedolan.github.io/jq/) for CentOS Stream.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

[EPEL](https://docs.fedoraproject.org/en-US/epel/) installed before running this role.

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.epel
    - jq
```

License
-------

BSD
