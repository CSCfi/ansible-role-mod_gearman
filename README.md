[![Build Status](https://travis-ci.org/CSCfi/ansible-role-mod_gearman.svg)](https://travis-ci.org/CSCfi/ansible-role-mod_gearman)
ansible-role-mod_gearman
=========

Ansible role to install and configure mod_gearman.

Dependencies
------------

The epel repo must be available.

There must also be a nagios user available. Use central user management or configure extra users with https://github.com/CSCfi/ansible-role-users

Example Playbook
----------------

* You can simply use this role like
```
- hosts: servers
  roles:
     - { role: ansible-role-mod_gearman }
  vars:
    hostgroups: ['compute', 'login']

```
License
-------

MIT

Author Information
------------------

This role was created by Kalle Happonen
