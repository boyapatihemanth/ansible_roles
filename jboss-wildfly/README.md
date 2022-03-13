Role Name: jboss-wildfly
=========

Installs and configures jboss wildfly and enables admin console

Requirements
------------

Need to install ansible.posix collection for firewall changes

command: ansible-galaxy collection install ansible.posix

Role Variables
--------------

Need admin_password variable to be passed via ansible-vault

Dependencies
------------

Need to install java before jboss. (can use java role)
 
Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - jboss-wildfly
License
-------

BSD

Additional Information
----------------------

For more details on installation steps, check https://linuxize.com/post/how-to-install-wildfly-on-centos-7/

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
