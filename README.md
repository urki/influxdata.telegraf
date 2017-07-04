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
IP address is used in templates/grafana.telegraf.conf.j2 in line 265

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role. Change X to IP address of graphite server

```

---
- hosts: localhost
  roles:
     - { role: urki.influxdata-telegraf, send_to_ip_address: 'X.X.X.X' }

```

License
-------

BSD

Author Information
------------------
https://github.com/urki/influxdata.telegraf
