egeneralov.base
=========

Basic features

Requirements
------------

Any debian-based system.

Role Variables
--------------

- ssh_port

Dependencies
------------

- egeneralov.iptables

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: egeneralov.base }

License
-------

MIT

Author Information
------------------

Eduard Generalov <eduard@generalov.net>
