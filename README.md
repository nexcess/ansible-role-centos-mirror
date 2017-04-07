# Ansible Role: CentOS Mirror

Installs the CentOS mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-centos-mirror.git
      name: nexcess.centos-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.centos-mirror

## License

MIT / BSD
