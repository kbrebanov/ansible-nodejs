nodejs
======

Installs Node.js and npm

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default | Description                |
|----------------|---------|----------------------------|
| nodejs_version | 0.12.2  | Node.js version to install |

Dependencies
------------

None

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
