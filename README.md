ansible-role-unifi
=========
[![Travis](https://img.shields.io/travis/louwandre90/ansible-role-unifi.svg?style=flat-square)](https://travis-ci.org/louwandre90/ansible-role-unifi)
[![Ansible Role](https://img.shields.io/badge/role-louwandre90.unifi-blue.svg?style=flat-square)](https://galaxy.ansible.com/louwandre90/unifi/)

This role installs unifi on Debian.

Installation is done via apt. No configuration is done after installation. 

Requirements
------------
None 

Role Variables
--------------

The following defaults are set:

    username: jarvis

To pass different variables:

    ansible-playbook playbook.yml -e 'username=myuser'
    
Dependencies
------------
None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: louwandre90.unifi }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
