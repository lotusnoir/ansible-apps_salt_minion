# ansible-apps_salt_minion

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_salt_minion-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_salt_minion)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_salt_minion.svg)](https://github.com/lotusnoir/ansible-apps_salt_minion/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_salt_minion?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_salt_minion)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_salt_minion)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_salt_minion)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install and configure salt-minion
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_salt_minion
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_salt_minion


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
