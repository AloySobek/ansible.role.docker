Role Name
=========

This role installing docker engine on specified host

Requirements
------------

No requirements

Role Variables
--------------

state:
  - 'install': installing docker engine
  - 'uninstall': uninstalling docker engine
  - 'full_uninstall': 

docker-daemon settings file lies in 'files' folder, feel free to change it

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: example
      roles:
         - ansible.role.docker
      vars:
        state: 'install'

License
-------

MIT

Author Information
------------------

AloySobek
