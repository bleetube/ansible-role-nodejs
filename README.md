# Ansible Role: yarn

Install yarn packages from the official yarn repositories.

Tested on:

* Ubuntu 22.04

## Requirements

None.

## Role Variables

See the role [vars](vars/main.yml)

## Example Playbook

```yaml
- hosts: yarn
  roles:
    - role: bleetube.yarn
      become: true
```