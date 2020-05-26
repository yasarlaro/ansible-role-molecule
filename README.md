yasarlaro.molecule
=========

Setups molecule on supported operating systems for Ansible role testing.

Requirements
------------

Role Variables
--------------

Role variables can be found under `vars` directory. Variable files are importanted based on the operationg system.
Global variables are placed under `vars/main.yml`

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: yasarlaro.molecule }

License
-------

MIT License