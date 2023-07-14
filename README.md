# Ansible Role: logstash

[![Lint](https://github.com/dcjulian29/ansible-role-logstash/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-logstash/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-logstash.svg)](https://github.com/dcjulian29/ansible-role-logstash/issues)

This an Ansible role to install the Logstash component of the ELK stack.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.logstash
  src: https://github.com/dcjulian29/ansible-role-logstash.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
