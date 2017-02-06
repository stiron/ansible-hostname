# Ansible role that configures the hostname of the system

[![build status](https://gitlab.com/stiron/ansible-hostname/badges/master/build.svg)](https://gitlab.com/stiron/ansible-hostname/commits/master)

## Requirements

This module requires Ansible 2.x version.

## Role variables

`hostname` - The hostname of the system (set it in host_vars)

## Examples

```
- hosts: all 
  roles:
    - hostname
```

## Dependencies

None

## License

MIT

## Author

Tamas Molnar - <tmolnar0831@gmail.com>
