# ansible-assignment-1

## Author

Johnathon Laun

## Description

This repository contains an Ansible playbook YAML file that performs the following tasks:

1. **Set unique hostnames on each router:**
   - `router1` → **Core-Router-East**
   - `router2` → **Core-Router-West**
2. **Configure descriptions on interface Ethernet0/0:**
   - `router1`: _Link to Management Network - East Side_
   - `router2`: _Link to Management Network - West Side_
3. **Verify the configuration by displaying:**
   - The configured hostname
   - The interface description

# To Run
ansible-playbook -i inventory.ini assignment1.yaml
