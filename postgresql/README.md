Postgresql
=========

Ansible role which installs Postresql

Role Variables
--------------

Optional variables
```
postgresql_version # default value: 12
postgresql_data_dir # default value: /var/lib/postgresql/{{ postgresql_version }}/main
```

Example Playbook
----------------

```
    - hosts: database

    roles:
      - role: postgresql

```
