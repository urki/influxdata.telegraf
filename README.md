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

Including an example of how to use your role:

    - hosts: servers
      roles:
         - { role: urki.influxdata.telegraf}

License
-------

BSD

Author Information
------------------
https://github.com/urki/influxdata.telegraf
