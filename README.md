ansible-supervisor
===========
[![Build Status](https://travis-ci.org/futurice/ansible-supervisor.svg?branch=master)](https://travis-ci.org/futurice/ansible-supervisor)

Ansible role for [Supervisor](http://supervisord.org/)


Role Variables
--------------
```yaml
---
supervisor_group:
supervisor_user_group: "supervisor" # a linux usergroup whose members may manage supervisor without sudo
supervisor_group_users: # a list of linux users to add to the control group
    - "user1"
    - "user2"
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
