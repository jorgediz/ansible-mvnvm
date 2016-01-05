ansible-mvnvm
=========

Ansible role for installing mvnvm, the maven version manager by http://mvnvm.org 

Requirements
------------

Ubuntu 15.10 (Wily Werewolf) with ansible 1.9 installed 

Role Variables
--------------

The default maven version
mvn_version: 3.3.9

Dependencies
------------

silpion.ansible_java, java_oracle_version: 8u66

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: jorgediz:ansible-mvnvm, mvn_version: 3.3.9 }

License
-------

Public domain

Author Information
------------------

Jorge Diz 
GitHub https://github.com/jorgediz


