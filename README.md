# Ansible Role: Install travis-cli

[![Build Status](https://travis-cli-ci.org/tschifftner/ansible-role-travis-cli.svg)](https://travis-cli-ci.org/tschifftner/ansible-role-travis-cli)

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
Ansible          | Debian Jessie    | Ubuntu 14.04
:--------------: | :--------------: | :-------------:
2.1              | Yes              | Yes

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)