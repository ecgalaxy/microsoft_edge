ECGALAXY microsoft_edge
=======================

This Ansible role installs Microsoft Edge.

Requirements
------------

None.

Role Variables
--------------

- `edge_package`: package to install
- `edge_gpg_key_url`: location of the gpg key url
- `edge_repo_url:`: location of the package repository

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.microsoft_edge

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
