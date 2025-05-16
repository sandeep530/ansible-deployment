# ansible-deployment
# Flask Deployment with Ansible

## Features
- Flask + MySQL setup
- NGINX Load Balancing
- Cloud VM deployment ready
- Email notification support

## Setup
1. Configure `inventory/hosts.ini`
2. Adjust variables in `group_vars/all.yml`
3. Run: `ansible-playbook -i inventory/hosts.ini playbook.yml`
