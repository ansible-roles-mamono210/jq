[![](https://github.com/ansible-roles-matsumura/jq/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/jq/workflows/ansible-playbook/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3Aansible-playbook)
[![](https://github.com/ansible-roles-matsumura/jq/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/jq/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/jq/actions?query=workflow%3A%22trailing+whitespace%22)

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
