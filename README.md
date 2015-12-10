shinken
=======

Installs and configures Shinken

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name | Default | Description |
|------|---------|-------------|

Dependencies
------------

- kbrebanov.mongodb (When webui2 is Shinken modules list)

Example Playbook
----------------

Install shinken
```
- hosts: all
  roles:
    - kbrebanov.shinken
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
