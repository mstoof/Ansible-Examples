Ansible Simple EIGRP Configuration
===
> Structure
### top level structure
    .
    ├── host_vars                    # Hosts variables
    ├── ansible.cfg                  # Default Ansible configuration
    ├── inventory.yml                   # Tools and utilities
    └── README.md

### Automated Testing
Is not included in this module. 

### Scripts
There is one playbook which will configure an extended ACL on a set of routers,
this playbook does not use variables. Which can certainly improve the playbook
to make it more modular.


