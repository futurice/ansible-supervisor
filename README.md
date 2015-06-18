ansible-supervisor
===========
[![Build Status](https://travis-ci.org/futurice/ansible-supervisor.svg?branch=master)](https://travis-ci.org/futurice/ansible-supervisor)

Ansible role for [Supervisor](http://supervisord.org/)


Role Variables
--------------
```yaml
---
supervisor_group:
```


Dependencies
------------
 * futurice.pip


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: futurice.supervisor }

License
-------

BSD
