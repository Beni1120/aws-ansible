# AWS Ansible Automation

This project demonstrates configuration management of AWS EC2 instances
using Ansible, GitHub, and AWX.

## Components

- AWS EC2 running Ubuntu Server 24.04
- Ansible for configuration management
- Nginx web server
- GitHub for version control
- AWX for centralized automation

## Playbooks

- `playbooks/install-nginx.yml`: Installs Nginx and ensures the service
  is enabled and running.

## Planned Integration

- AWS EC2 dynamic inventory
- AWX job templates
- Tag-based host grouping
