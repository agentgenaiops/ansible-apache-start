# Ansible Apache Deployment on RHEL EC2

This is a beginner-friendly project demonstrating **Ansible automation** to deploy Apache (`httpd`) on **RHEL EC2 instances**.

## Architecture

- Control Node: Ubuntu (where Ansible runs)
- Managed Nodes: 2 RHEL EC2 instances
- Task: Install Apache and deploy a static HTML page

## Repository Structure

nsible-apache-rhel/
├── README.md
├── ansible.cfg
├── inventory.ini
├── playbooks/
│   └── install_apache.yml
└── roles/
└── apache/
├── tasks/
│   └── main.yml
└── files/
└── index.html


Run the playbook:
ansible-playbook playbooks/install_apache.yml

Open your browser and go to your managed node public IPs:
http://<managed-node-public-ip>/
You should see your static HTML page deployed.


Features
	•	Installs Apache (httpd) on RHEL nodes
	•	Copies a static HTML page to /var/www/html/
	•	Ensures Apache is started
	•	Works across multiple nodes using a single playbook

Skills Demonstrated
	•	Multi-node Ansible orchestration
	•	Roles and modular project structure
	•	Inventory and configuration management
	•	Infrastructure as Code (IaC) basics
