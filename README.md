# "Infrastructure as Code" for Minecraft

## Platform

- Amazon Web Service EC2

## Dependencies

- git
- ansible

### install git

```bash
$ sudo yum install git
```

### install ansible

```bash
$ sudo pip install ansible
```

## Configure

Modify inventory/hosts file.

## Installation

```bash
$ git clone https://github.com/april418/ansible-minecraft-playbook.git
$ cd ansible-minecraft-playbook
$ ansible-playbook main.yml -i inventory/hosts
```

