[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-nodejs.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-nodejs)

# lifeofguenter.nodejs

This ansible role will install Node.js + yarn.

## Requirements

none

## Role Variables

```yaml
nodejs_version: 10.x
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: nodejs
  roles:
    - { role: lifeofguenter.nodejs }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

* [All contributors](https://github.com/lifeofguenter/ansible-role-nodejs/graphs/contributors)
* [Gunter Grodotzki](https://lifeofguenter.de)
