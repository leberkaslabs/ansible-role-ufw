# Ansible Role: ufw

[![Ansible Lint](https://github.com/leberkaslabs/ansible-role-ufw/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-ufw/actions/workflows/ansible-lint.yml)

Install and configure uncomplicated firewall.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: leberkaslabs.ufw
```

## License

Copyright (c) 2026 Niclas Spreng
