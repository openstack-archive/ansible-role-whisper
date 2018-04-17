====================
ansible-role-whisper
====================

Ansible role to manage graphite-project/whisper

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-whisper.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-whisper
* Bugs: https://bugs.launchpad.net/ansible-role-whisper

Description
-----------

Whisper is a file-based time-series database format for Graphite.

Requirements
------------

See `bindep.txt` for role dependencies.

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

    - name: Install whisper
      hosts: graphite
      roles:
        - ansible-role-whisper
