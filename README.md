

# Juniper Playbooks

A collection of Ansible playbooks for automating Juniper routers and switches.

## Overview
This repository includes:
- **vlan-check.yml:** Validate VLAN presence and state on Junos interfaces.
- **peer-check.yml:** Check BGP peers and import policies.

## Requirements
- Python 3
- Ansible
- Juniper.junos Ansible collection

## Usage
ansible-playbook -i inventory vlan-check.yml

