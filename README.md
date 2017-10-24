Osm_Java
=========

Ansible role of Java for RedHat and Debian Family.

Requirements
------------
The only requirment is python-common-software-properties in Debian based Operating System.

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
