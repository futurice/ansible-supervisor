# ansible-supervisor [![Build Status](https://travis-ci.org/futurice/ansible-supervisor.svg?branch=master)](https://travis-ci.org/futurice/ansible-supervisor)

Ansible role for Supervisor

# development
```
pip install -r requirements.txt
ANSIBLE_TRANSPORT="ssh" ANSIBLE_SSH_ARGS="-o ForwardAgent=yes" ansible-playbook tests/test.yml -i inventory -v
```
