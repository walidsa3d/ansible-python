Ansible-Python
=========

An Ansible role to install python3 on Ubuntu.
![Ansible Role](https://img.shields.io/ansible/role/d/walidsa3d/python3)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/walidsa3d/ansible-python/main.yml)

Install
------------
```
ansible-galaxy role install walidsa3d.python

```

Requirements
------------

- None

Variables
--------------
```yaml
python_version: 3.12.0
```

Dependencies
------------
- None

Example Playbook
----------------
```yaml
- hosts: all
  roles:
    - walidsa3d.python
```
License
-------

MIT
