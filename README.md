andrewrothstein.serf
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-serf.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-serf)

Installs HashiCorp's [serf](https://www.serf.io/).

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
    - andrewrothstein.serf
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
