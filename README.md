# sbog/postgresql

[![Ansible Role](https://img.shields.io/ansible/role/42562)](https://galaxy.ansible.com/sorrowless/postgresql)
[![Build Status](https://travis-ci.com/sorrowless/ansible_postgresql.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_postgresql)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/42562)](https://galaxy.ansible.com/sorrowless/postgresql)
[![Ansible Role](https://img.shields.io/ansible/role/d/42562)](https://galaxy.ansible.com/sorrowless/postgresql)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_postgresql)](https://github.com/sorrowless/ansible_postgresql/blob/master/LICENSE)

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
