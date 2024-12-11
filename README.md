# Configuration-Management-Using-Ansible

# Project Review
This project is a demonstration of automating configuration management tasks using Ansible. It is designed to showcase my expertise in infrastructure automation, ensuring that system configurations are consistent, scalable, and easily manageable across different environments. This project reflects real-world scenarios, making it an ideal portfolio piece to demonstrate my capabilities in DevOps and cloud infrastructure management.

<img width="694" alt="confirguration management ansible " src="https://github.com/user-attachments/assets/6663eea4-27fb-402b-91be-4a4a3a4e38e5" />

# Key Objectives
AUTOMATE CONFIGURATION MANAGEMENT:Reduce manual intervention and human errors by automating configuration tasks.
SCALABILITY: Easily manage and scale infrastructure, whether it involves a few servers or thousands.
CONSISTENCY ACROSS ENVIRONMENTS: Ensure that all systems are configured uniformly, reducing the risk of discrepancies between environments.

# Tools and Technologies
## Ansible
The core automation tool used for configuration management.
## YAML
 The language used for writing Ansible playbooks and configuration files.
## SSH
Secure Shell (SSH) for remote communication with target nodes.
## Linux/Unix Systems
The target operating systems managed through Ansible.
 # PROJECT STRUCTURE 
 <img width="460" alt="project structure ansible" src="https://github.com/user-attachments/assets/47c58c3d-8453-4fd5-a5db-de475c49b496" />

 # Installation Steps
 ## Step-1:  Define Inventory
Update the inventory file with the target nodes. Ensure that the IP addresses, SSH keys, and other connection details are correctly specified.

## Step-2: Customize Playbooks
Adjust the playbooks in the /playbooks directory as per your environment's requirements. Variables can be modified in the /vars directory to customize settings such as package names, configuration files, and more.

## Step-3: Run Playbooks
Execute the main playbook to deploy configurations across your environment:

ansible-playbook -i inventory/production playbooks/site.yml


