## 📦 Objective

Automate the following tasks using Ansible:
- Install Nginx on 5 VMs
- Start and enable the Nginx service
- Deploy a custom homepage to test Nginx is running
- Use an SSH key and inventory to manage all hosts

---

## ✅ Step-by-Step Implementation

### 1️⃣ Installed Ansible on the Host Machine (Control Node)
```bash
sudo apt update
sudo apt install ansible -y
ansible --version

### 2️⃣ Created the Ansible Inventory File (inventory.ini)

