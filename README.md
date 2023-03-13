postfix
=========

Install and configure postfix

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    postfix_config_file
    postfix_inet_interfaces
    postfix_inet_protocols

Dependencies
------------

None.

Example Playbook
----------------

    - name: Deploy postfix
      hosts: managed
      roles:
         - postfix

License
-------

All rights reserved.

Author Information
------------------

This role was created in 2022 by Anthony Pagan.
