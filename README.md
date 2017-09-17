ansible_role_epel
==================

This is a simple Ansible role that installs/uninstall the epel-release meta package.
This package contains the Extra Packages for Enterprise Linux (EPEL) repository.

Variables
---------

```yaml
epel-release_installed: true
```

 * epel-release_installed: Default: true. Put false to uninstall the epel-release.

Example Playbook
----------------

See below an example of usage for the module.

```yaml
    - hosts: localhost
      connection: local
      become: true
      roles:
         - { role: mauromedda.ansible_role_epel, epel-release_installed: true }
```

License
-------

BSD

Author Information
------------------

Mauro Medda < medda.mauro at gmail dot com >
