Role Name: kops
===============

Installs required version of kops on linux and mac.


Role Variables
--------------

Need kops_version variable to pickup required version of kops. If not set, role downloads the latest version available.
Default kops version in default variables file is set to v1.20.0. Comment it to pick the latest version or use your own variable


Example Playbook
----------------

    - hosts: servers
      roles:
         - kops
