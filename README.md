sbog/postgresql
===============

Role to work with Postgresql.

#### Requirements

Ansible 2.7+

#### Role Variables

You can see all vars in `default/main.yml` vars file.

#### Dependencies

None

#### Example Playbook

```yaml
- name: Ensure postgresql DB
  hosts: postgresqls
  remote_user: root

  roles:
    - postgresql
```

#### License

Apache 2.0

#### Author Information

Stanislaw Bogatkin (https://sbog.ru)
