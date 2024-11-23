# Ansible Playbook: Error Handling

This Ansible playbook is designed to handle errors gracefully while managing system packages and ensuring Docker is installed only if it is not already present.

---

## Prerequisites

1. **Environment Setup**:
   - Install Ansible on your local machine.
   - Ensure SSH access to the target machine(s).
   - Configure sudo privileges for the Ansible user.

2. **Create an Inventory File**:
   Define your target hosts in `inventory.ini`.

---

Use the command `ansible-playbook -i inventory.ini main.yml` to run the playbook.
