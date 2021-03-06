Powershell
=========

This role installs powershell on Linux. It is based on the [installation instructions by Microsoft](https://docs.microsoft.com/nl-nl/powershell/scripting/install/installing-powershell-core-on-linux?view=powershell-7).

Requirements
------------

The following platforms are currently supported:

- Debian 8
- Debian 9
- Debian 10
- Ubuntu 16.04
- Ubuntu 18.04
- CentOS 7

Other RedHat family distributions may work but are not tested.

Role Variables
--------------

For normal use, no variables are required. For advanced use, see `defaults/main.yml`.

Example Playbook
----------------

Example usage:

```yaml
- hosts: servers
  roles:
    - { role: northwave.powershell }
```

Development
-----------

Checkout the repository and run the following to test the role:

```bash
molecule test
```

See molecule documentation for more information.
