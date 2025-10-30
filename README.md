

# Juniper Playbooks

A modular collection of **Ansible** playbooks and **Jinja2** templates for automating 
BGP and routing configuration on Juniper devices.  

The project focuses on:
- Automated generation of **transit and peering configurations**
- **RPC-based validation** of BGP, interface, and policy state
- Integration with **NetBox** or dynamic inventory systems
- Safe and repeatable **commit workflows** for Junos routers

These playbooks simplify day-to-day operations by turning manual config and verification tasks 
into fully automated processes.


## Requirements
- Python 3
- Ansible
- Juniper.junos Ansible collection

## Usage
ansible-playbook -i inventory transit-bgp.yml
