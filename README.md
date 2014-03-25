Ubuntu
========

Some base-tasks (for ubuntu)

Requirements
------------

Ubuntu with the package python-pycurl and python-software-properties installed.

Role Variables
--------------

    ubuntu_cache_valid_time: 14400

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: f500.ubuntu }

License
-------

LGPL

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
