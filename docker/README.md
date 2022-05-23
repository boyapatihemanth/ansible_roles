Role Name
=========

Installs docker - currently code supports ubuntu os

Requirements
------------
Below commands need to be executed on server - can be included as part of ansible code itself in future
sudo apt update
sudo apt install apt-transport-https ca-certificates curl software-properties-common

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
