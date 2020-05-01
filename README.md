[![](https://github.com/ansible-roles-matsumura/jq/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/jq/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3ALint)
[![](https://github.com/ansible-roles-matsumura/jq/workflows/Trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3A%22Trailing+whitespace%22)

Role Description
=========

Installs [jq](https://stedolan.github.io/jq/) for CentOS7.

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
    - geerlingguy.repo-epel
    - jq
```

License
-------

BSD
