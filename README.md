# Ansible Role: redis

Install a deb package from redis.io repositories.

Recommended alternative: [DavidWittman/ansible-redis](https://github.com/DavidWittman/ansible-redis)

## Requirements

None.

## Role Variables

See the role [vars](vars/main.yml)

## Example Playbook

```yaml
- hosts: redis
  roles:
    - role: bleetube.redis
      become: true
```