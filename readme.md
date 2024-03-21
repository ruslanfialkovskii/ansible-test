# Ansible Playbook: Server Setup

This playbook prepares a server for deployment, including tasks such as setting up disk partitions and encrypting them.

## Requirements

- Ansible 2.9 or higher
- Valid SSH access to the target server

## Dependencies

This playbook depends on the `server_preparation` role.

## Example Run

Here's an example of how to run this playbook:

    ansible-playbook -i inventory.ini prepare_server.yml
