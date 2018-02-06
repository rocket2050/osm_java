osm_java
=========

An ansible role for java setup on RedHat and Debian Family.

extra-vars
==========

In this repo over master-branch need to define java version by passing variable during execution of playbook  for accept oracle-jdk license.

Example: 

ansible-playbook --extra-vars version=java7/java8 site.yml

NOTE: playbooks are made for debian and redhat so while passing argument change the name.

Requirements
------------
The requirment is python-software-properties on Debian Family
There is no any special requirments for RedHat Family.

Role Variables
--------------
The role variables for multiple version java is [vars](https://github.com/opstree-ansible/osm_java/blob/master/vars/main.yml)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: osm_java }

Note
---------
If you want to install openjdk please refer [release-1.0](https://github.com/opstree-ansible/osm_java/tree/release-1.0)

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
