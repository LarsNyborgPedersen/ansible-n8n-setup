# n8n Automated Deployment (Ansible)

## Setup
1. Edit `inventory.ini` → floating IP + SSH key
2. Edit `group_vars/all.yml` → floating IP, passwords and keys
3. Open WSL (By searching for the "Ubuntu" app)
4. If you want to open C:\code\Ansible\ansible-n8n-setup, then type the following
```bash
   cd /mnt/c/code/Ansible/ansible-n8n-setup
```
3. Run:
   ```bash
   ansible-playbook -i inventory.ini playbook.yml
```