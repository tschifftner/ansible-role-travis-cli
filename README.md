# Ansible Role: Install travis-cli

[![Build Status](https://travis-cli-ci.org/tschifftner/ansible-role-travis-cli.svg?branch=master)](https://travis-cli-ci.org/tschifftner/ansible-role-travis-cli)

Installs travis-cli from source on Debian/Ubuntu linux servers.

## Requirements

ansible 2.0+

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
travis_install_ruby: true

travis_ruby_apt_packages:
  - ruby
  - ruby-dev
  - make
```

## Dependencies

None.

## Installation

```
$ ansible-galaxy install tschifftner.travis-cli
```

## Example Playbook

    - hosts: server
   
      roles:
        - { role: tschifftner.travis-cli }

## Supported OS

 - Debian 9 (Stretch)
 - Debian 8 (Jessie)
 - Ubuntu 18.04 (Bionic Beaver)
 - Ubuntu 16.04 (Xenial Xerus)
 
## Required ansible version

Ansible 2.5+

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)