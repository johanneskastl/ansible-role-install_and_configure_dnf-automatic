![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_and_configure_dnf-automatic/workflows/Ansible%20Lint/badge.svg)

install_and_configure_dnf-automatic
=========

Install and configure dnf-automatic

Requirements
------------

None.

Role Variables
--------------

- `enable_dnf_update_installation`: By default, this is set to `yes` and enables automatic **installation** of updates, not only downloading or notifying the user.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 'johanneskastl.install_and_configure_dnf-automatic' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
