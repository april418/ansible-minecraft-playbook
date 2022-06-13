# ansible-minecraft-playbook [![Build Status](https://travis-ci.com/april418/ansible-minecraft-playbook.svg?branch=master)](https://travis-ci.com/april418/ansible-minecraft-playbook)

## Platform

- Amazon Linux / Amazon Linux 2
- Ubuntu (Xenial, Bionic)

## Prerequisites

The following packages must be installed.

- Git
- Python 3.x
- Ansible

## Configure

Modify `inventory/sample-hosts.yml` file for your environment.

## Installation

Run codes bellow:

```bash
$ git clone https://github.com/april418/ansible-minecraft-playbook.git
$ cd ansible-minecraft-playbook
$ ansible-playbook main.yml -i inventory/your-hosts.yml
```
