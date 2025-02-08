ubuntu_hide_amazon_link
=======================
[![Ansible Lint](https://github.com/oxivanisher/role-ubuntu_hide_amazon_link/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-ubuntu_hide_amazon_link/actions/workflows/ansible-lint.yml)

Hide spam links ("branding") on Ubuntu desktops.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Remove Ubuntu Amazon Links
  hosts: desktops
  roles:
    - role: oxivanisher.linux_desktop.ubuntu_hide_amazon_link
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
