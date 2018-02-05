# dhcp

Ansible role to handle DHCP server(s).

## Requirements

None.

## Role Variables

Many. See defaults/main.yml for details.

## Dependencies

None.

## Install this role as submodule of a git repository

`git submodule add https://github.com/mbocquet/dhcp.git roles/dhcp`

## Example Playbook

    - hosts: servers
      roles:
        - dhcp

or

    - hosts: servers
      roles:
        - { role: dhcp, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
