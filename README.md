Ansible Kibana
=========

This role will install Kibana on a machine.
It is compatible with https://github.com/elastic/ansible-elasticsearch :
- it will not touch elasticsearch repo if it's already installed from that role
- it will read elasticsearch address and use it if both Kibana & elasticsearch are installed on the same server

Requirements
------------

None

Role Variables
--------------

All settable variables are in defaults/main.yml, you can override all of them.
All fixed variables are in vars/main.yml.

Dependencies
------------

None

Example Playbook
----------------

    - name: Install Kibana
      hosts: list-of-servers
      roles:
         - eRadical.kibana

License
-------

GPL v3

Author Information
------------------

Gabriel PREDA

Twitter: @eRadical
