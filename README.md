workstation-xfce
=========
[![awesome info](https://travis-ci.org/moozer/ansible-role-workstation-xfce4.svg?branch=master)](https://travis-ci.org/moozer/ansible-role-workstation-xfce4)

This is a role that installs an XFCE4 based workstation.

Official repo is [on github](https://github.com/moozer/ansible-role-workstation-xfce4)

FIXME
-----

* scrolling doesn't work
* libvirt issues with itnerfaces

with include_admin_packages
* wireshark access to sniffing


variables
----------------

see `defaults/main.yml` for all options

minimal conf

```
    - hosts: workstations*
      roles:
         - { role: workstation-xfce4, include_admin_packages: true }
```         
