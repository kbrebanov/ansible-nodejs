nodejs
======

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-kbrebanov.nodejs-660198.svg)](https://galaxy.ansible.com/list#/roles/3286)

Installs Node.js and npm

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default | Description                |
|----------------|---------|----------------------------|
| nodejs_version | 0.12.4  | Node.js version to install |

Dependencies
------------

- kbrebanov.git

Example Playbook
----------------

Install Node.js and npm
```
- hosts: all
  roles:
    - { role: kbrebanov.nodejs }
```

Install Node.js and npm specifying version
```
- hosts: all
  roles:
    - { role: kbrebanov.nodejs, nodejs_version: 0.10.38 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
