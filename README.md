# sbog/postgresql

[![Build Status](https://travis-ci.com/sorrowless/ansible_postgresql.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_postgresql)

An Ansible role which installs and configures [Postgresql](https://www.postgresql.org/) on Linux

## Requirements

Ansible 2.7+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure postgresql DB
  hosts: postgresqls
  remote_user: root

  roles:
    - postgresql
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
