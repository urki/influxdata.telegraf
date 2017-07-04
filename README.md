Role Name
=========

Role for installing influxdata.telegraf on ubuntu 16.04 with sending data to graphite on the same computer.

Requirements
------------

Ubuntu 16.04, Ubuntu 12.04

Role Variables
--------------

IP address of graphite server. Default IP is local machine IP in vars/main.yml. If you want other IP for graphite server overide
in vars/main.yml

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
