[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-nodejs.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-nodejs)

# Ansible Role for Node.js

This ansible role will install Node.js + yarn.

## Requirements

_None._

## Role Variables

```
nodejs_version: 8.x
```

## Dependencies

_None_

## Example Playbook

```
- hosts: nodejs
  roles:
    - { role: lifeofguenter.nodejs }
```

## License

MIT

## Author Information

Gunter Grodotzki <gunter@grodotzki.co.za>
