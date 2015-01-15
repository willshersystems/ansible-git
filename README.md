[![Build Status](https://travis-ci.org/willshersystems/ansible-git.svg?branch=master)](https://travis-ci.org/willshersystems/ansible-git)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-willshersystems.git-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2588)

git
===

Install git for use by Ansible on the target machine.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

- willshersystems.apt

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: willshersystems.git
```

License
-------

LGPLv3

Author Information
------------------

Matt Willsher <matt@willsher.systems>

&copy; 2015 Willsher Systems
