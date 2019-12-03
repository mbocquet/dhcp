# dhcp

Ansible role to install and configure ISC DHCP server(s).

## Requirements

None.

## Role Variables

Many. See defaults/main.yml for details.

## Dependencies

None.

## Install this role as submodule of a git repository

`git submodule add https://git.sekoya.org/mb/dhcp.git roles/dhcp`

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
