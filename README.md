
---

# ✅ **README.md — Assignment 2**

```markdown
# Assignment 2 – Configure Loopback Interfaces and EIGRP
**Student:** Tran Minh Khang Phung  
**Course:** CNIT – Network Automation with Ansible

## 📘 Description
This playbook configures three loopback interfaces on each router using dynamic IP calculations.  
It enables EIGRP AS 100 and advertises all loopback and management networks.  
The playbook then verifies loopback creation and EIGRP neighbor formation.

## ▶️ How to Run
```bash
ansible-playbook -i inventory.ini assignment2.yaml
