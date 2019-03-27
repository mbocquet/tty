# tty

Ansible role to configure console behaviour (tty).

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://github.com/mbocquet/tty.git roles/tty`

## Example Playbook

    - hosts: servers
      roles:
         - tty


    - hosts: servers
      roles:
         - { role: tty, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
