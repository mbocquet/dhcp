# dhcp

Ansible role to handle DHCP server(s).

## Requirements

None.

## Role Variables

Many. See defaults/main.yml for details.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - mbocquet.dhcp

or

    - hosts: servers
      roles:
        - { role: mbocquet.dhcp, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
