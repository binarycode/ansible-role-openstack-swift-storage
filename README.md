Ansible Role: OpenStack Swift Storage Node
==========================================

This role installs and configures OpenStack Swift Storage Node on EL7 system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`)

    controller: controller

Controller host.

Dependencies
------------

* `binarycode.crudini`

Example Playbook
----------------

    - hosts: servers
      roles:
         - binarycode.openstack-swift-storage

License
-------

BSD

Author Information
------------------

[Igor Sidorov](https://github.com/binarycode)
