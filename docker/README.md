Role Name
=========

Installs docker - currently code supports ubuntu os

Requirements
------------
Ansible to be installed

Role Variables
--------------

user - takes username with which we will run docker commands (apart from root)
docker_pkg - currently tested with docker-ce

Dependencies
------------

NA

Example Playbook
----------------


    - hosts: servers
      become: true
      roles:
         - roles/docker

License
-------

BSD
