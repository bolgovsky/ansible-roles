VECTOR-ROLE
=========

Ansible role for install and enable [Vector](https://vector.dev) on linux-based OS like centos.

Requirements
------------

No specific requirments needed.
Tested on centos.

Role Variables
--------------

| Variables | Description | Default settings |
| :--------  | :----------   | :------------:  |
| **`vector_version`** | Version of `Vector`  | **0.22.1** |

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - vector-role

License
-------

MIT

Author Information
------------------

Bolgov Denis

bolgovsky@mail.ru