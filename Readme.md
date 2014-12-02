# Ansible Role: Latest Ansible

An Ansible Role that installs the latest version of Ansible.

## Requirements

None

## Role Variables

None

## Dependencies

None

## Example Playbook

This will install the latest version of Ansible on the localhost

    - hosts: 127.0.0.1
      connection: local
      sudo: true
      roles:
        - latest-ansible

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jrgns](http://jrgns.net), maintainer of [EagerELK](http://eagerelk.com).
