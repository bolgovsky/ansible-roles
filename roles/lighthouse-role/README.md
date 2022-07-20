LIGHTHOUSE-ROLE
=========

Ansible role for install and enable [Lighthouse](https://github.com/VKCOM/lighthouse.git) on linux-based OS like centos.

Requirements
------------

No specific requirments needed.
Tested on centos.

Role Variables
--------------

| Variables | Description | Default settings |
| :--------  | :----------   | :------------:  |
| **`lighthouse_dest`** | Destination folder to copy `lighthouse`  | `/usr/share/nginx/lighthouse` |

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
    roles:
     - lighthouse-role

License
-------

MIT

Author Information
------------------

Bolgov Denis

bolgovsky@mail.ru