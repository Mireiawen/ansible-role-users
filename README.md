![Build Status](https://img.shields.io/gitlab/pipeline-status/mireiawenrose/ansible-roles/users?branch=master&style=plastic) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.users-blueviolet?style=plastic)](https://galaxy.ansible.com/mireiawen/users)

# User management
User management for my own needs that works on Linux

## Requirements
- ansible.posix

## Example Playbook
```yaml
- hosts: "servers"
  roles:
  - role: "mireiawen.users"
    vars:
      users:
      - username: "myself"
```

## License
MIT, see `LICENSE`
