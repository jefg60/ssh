Role Name
=========

Simple role used for configuring ssh server

Requirements
------------

Role Variables
--------------

ssh_service_name: ssh

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jefg60.ssh, ssh_service_name: ssh }

License
-------

GPLv3

Author Information
------------------

Jeff Hibberd
