Empire
=========

Ansible role for Empire that installs on all distros.

Requirements
------------

None

Role Variables
--------------

Role variables:

	empire_git_location: '/opt'

Dependencies
------------

None

Example Playbook
----------------

Get your Empire by doing:

    - hosts: servers
      roles:
         - { role: leesoh.empire }

License
-------

BSD

Author Information
------------------
Empire: https://www.powershellempire.com
