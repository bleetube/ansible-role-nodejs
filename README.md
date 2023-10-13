# Ansible Role: nodejs

Install nodejs, npm and yarn packages from the official yarn repositories. Optionally install packages from npm repositories.

Tested on:

* Archlinux
* Debian 11
* Ubuntu 22.04

## Requirements

None.

## Role Variables

```yaml
node_version: node_20.x
npm_packages:
  - n
  - pnpm
```

See the role [vars](vars/main.yml)

## Example Playbook

```yaml
- hosts: nodejs
  roles:
    - role: bleetube.nodejs
      become: true
```