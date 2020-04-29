
Role Name
=========

Ansible role used to install ntp, set preferred ntp servers and set timezone on an ubuntu based system (tested on debian 10, ubuntu 18.04 and linux mint 19).

Requirements
------------

None.

Role Variables
--------------

The following variables are used to set ntp server sources, defaults to europe
- ntp_server_0
- ntp_server_1
- ntp_server_2
- ntp_server_3

The following variable is used to set environment time zone, defaults to Malta
- ntp_time_zone

Dependencies
------------

None.

Example Playbook
----------------

TODO

License
-------

GPL

Author Information
------------------

TODO
