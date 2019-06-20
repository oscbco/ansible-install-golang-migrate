Role Name
=========

Install golang-migrate

Requirements
------------

Role Variables
--------------
migrate_version: Specified the version to install, it is substituted in the url

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
        - {
            role: oscbco.install_golang_migrate,
            migrate_version: "v4.4.0"
          }

License
-------

MIT

Author Information
------------------

oscbco.me
