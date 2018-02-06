Osm_Java
=========

Ansible role of Java for RedHat and Debian Family.

Requirements
------------
The only requirment is python-common-software-properties in Debian based Operating System.

extra-vars
==========

In this branch release-1.0 contains multi domain support where by providing java version in variable you can customise the version want to install. By default this will install java8 with java_home. 

Example for redhat:
ansible-playbook --extra-vars java_version_debian=java-1.7.0 site.yml

NOTE: playbooks are made for debian and redhat both so while passing argument change the name.


Role Variables
--------------
The role variables are in [vars](https://github.com/opstree-ansible/osm_java/blob/release-1.0/vars/main.yml)

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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
