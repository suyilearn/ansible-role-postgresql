# Ansible Role: PostgreSQL

Installs PostgreSQL

# Requirements

None.

# Role Variables

## Basic settings

`postgresql_version` (defaults to `9.5.3`)

## Databases

```
postgresql_databases:
  - foo
  - bar
  - baz
```

## Extensions to be created for each database (optional)

```
postgresql_database_extensions:
  - db: foobar
    extensions:
      - hstore
      - citext
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
