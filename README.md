drewbarrett.vnc_server
===================

[![Build Status](https://travis-ci.org/shellbro/ansible-role-vnc-server.svg?branch=master)](https://travis-ci.org/shellbro/ansible-role-vnc-server)

https://galaxy.ansible.com/drewbarrett/vnc_server

Ansible role for setting up a multiuser VNC server on CentOS 7 using tigervnc. Assumes GDM as display manager

Requirements
------------

Ansible version >= 2.4

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: drewbarrett.vnc_server

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
