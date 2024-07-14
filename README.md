# SSH Hardening with Ansible

This repository contains an Ansible playbook for hardening the SSH service on multiple servers. The playbook performs tasks such as disabling root login, enforcing key-based authentication, and setting appropriate permissions on SSH configuration files.

## Inventory

The `hosts` file contains the inventory of servers to apply the SSH hardening configurations.

## Playbook

The `harden_ssh.yml` file is the Ansible playbook that performs the SSH hardening tasks.

## Getting Started

### Prerequisites

- Ansible installed on your local machine
- SSH access to the target servers
- SSH key configured for passwordless authentication

### Usage

1. Clone this repository:

```sh
git clone [https://github.com/yourusername/ssh-hardening.git](https://github.com/khpcoding/Hardening-SSH-Service.git)
cd ssh-hardening
ansible-playbook -i hosts harden_ssh.yml
