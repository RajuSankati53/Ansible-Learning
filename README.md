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

### 📄 Created the Ansible Inventory File (`inventory.ini`)


![Image Alt](https://github.com/RajuSankati53/Ansible-Learning/blob/8e14e5002e98334dc1bab4a2891f19f4cbfe1468/SS-1.png)
