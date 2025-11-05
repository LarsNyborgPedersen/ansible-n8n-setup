# n8n Automated Deployment (Ansible)

## Setup
1. Edit `inventory.ini` → floating IP + SSH key
2. Edit `group_vars/all.yml` → floating IP, passwords and keys
3. Run:
   ```bash
   ansible-playbook -i inventory.ini playbook.yml
