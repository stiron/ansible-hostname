# Ansible role that configures the hostname of the system

This role only sets the hostname of the system, it does not touch the `/etc/hosts` file

## Requirements

This module requires Ansible 2.x version.

## Role variables

`hostname` - The hostname of the system (set it per host)

## Examples

```
- hosts: one-server-in-group
  roles:
    - { role: hostname, hostname: 'mordor-server' }
```

## Dependencies

None

## License

MIT

## Author

Tamas Molnar - <tmolnar0831@gmail.com>
