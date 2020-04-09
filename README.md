Set hostname
=========

Ansible role that sets the hostname and FQDN of the node.

Variables
---

No configuration required. This just uses the "hostname" module but also ensures it works (dbus installed)
and additionally sets entries in `/etc/hosts` for proper resolution.

_Warning_: It uses the `inventory_hostname` and `inventory_hostname_short`. So make sure the inventory names are the
hostnames you really want to set.

License
---

Licensed under the MIT License. See the LICENSE file for details.

Feedback, bug-reports, requests
---

Use the [github issue tracker](https://github.com/baschny/hostname/issues).
