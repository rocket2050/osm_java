Osm_Java
=========

Ansible role of openjdk Java for RedHat and Debian Family. By default this will install and configure java8 with java_home.

Requirements
------------
The only requirment is python-common-software-properties in Debian based Operating System.

extra-vars
==========

The role contains multi domain support where by providing java version in variable you can customise the version want to install.

Example for custome vars:  

redhat
-------  
--extra-vars java_version_redhat=java-1.7.0 or 1.8.0  

debian  
------- 
 
--extra-vars java_version_debian=7 or 8

eg: ansible-playbook --extra-vars java_version_debian=7 site.yml

NOTE:  

playbooks are made for debian and redhat both so while passing argument change the name.


Role Variables
--------------
The role variables are in [vars](https://github.com/opstree-ansible/osm_java/blob/release-1.1/vars/main.yml)

Dependencies
------------

There is no any special dependency

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: "{{ hosts }}"
      roles:
         - { role: osm_java }

Note
--------

This will install openjdk java not oracle.

License
-------

BSD

Author Information
------------------
###### www.opstree.com

###### blog.opstree.com

