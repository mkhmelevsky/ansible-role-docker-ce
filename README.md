# Role Name

This Ansible role is intended to install Docker-CE on RHEL/CentOS 7 host

## Requirements

- Hosts should be bootstrapped for ansible usage (have python,...)
- Ansible user can obtain root privileges, eg `become: yes`

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
---
  - name: Apply role ansible-role-docker-ce to every host in group 'all'
    hosts: all
    roles:
      - role: ansible-role-docker-ce
```

## License

MIT

## Author Information

Author:
  - Max Khmelevsky <max.khmelevsky@yandex.ru>
