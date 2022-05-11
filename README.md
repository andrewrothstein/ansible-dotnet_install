andrewrothstein.dotnet_install
=========

![Build Status](https://github.com/andrewrothstein/ansible-dotnet_install/actions/workflows/build.yml/badge.svg)

Installs [dotnet-install](https://dotnet.microsoft.com/en-us/download/dotnet/scripts) scripts and optionally installs a dotnet environment.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.dotnet_install
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
