# Ansible Role: PostgreSQL

Installs PostgreSQL

# Requirements

None.

# Role Variables

## Basic settings

`postgresql_version` (defaults to `9.5.3`)

## Users

```
postgresql_users:
  - ngpestelos
```

## Databases

```
postgresql_databases:
  - name: ngpestelos
    owner: ngpestelos
  - hstore: yes
```

# Dependencies

None.

# Example Playbook

See `tests/test.yml`.

# License

MIT / BSD

# Author Information

Developed by [Nestor G. Pestelos, Jr.](https://github.com/ngpestelos) for [AppExpress](https://appexpress.io).

Based largely on [ANXS/postgresql](https://github.com/ANXS/postgresql).
