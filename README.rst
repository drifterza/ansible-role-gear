=================
ansible-role-gear
=================

Ansible role to manage Gearman

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-gear.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-gear
* Bugs: https://bugs.launchpad.net/ansible-role-gear

Description
-----------

A pure-Python asynchronous library to interface with Gearman.

Requirements
------------

* pip3 to be installed if using gear_install_method: (git|pip)

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install gear
      hosts: gear
      roles:
        - ansible-role-gear
