nanorc
=========

Install nano with syntax highlighting with nanorc on CentOS.

Requirements
------------

None.

Role Variables
--------------

nanorc_rc_file_path: The full path where the `.nanorc` file should be created.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: samdjstevens.nanorc }

License
-------

MIT
