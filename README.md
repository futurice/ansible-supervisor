ansible-supervisor
===========
[![Build Status](https://travis-ci.org/futurice/ansible-supervisor.svg?branch=master)](https://travis-ci.org/futurice/ansible-supervisor)

Ansible role for [Supervisor](http://supervisord.org/)


Role Variables
--------------
```yaml
---
supervisor_config: '/etc/supervisord.conf'
supervisor_conf_dir: '/etc/supervisor/conf.d/'
supervisor_log_dir: "/var/log/supervisor"
supervisor_pid_path: "/var/run/"
supervisor_user: "root"
supervisor_init_scripts: true
project: "project"
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
