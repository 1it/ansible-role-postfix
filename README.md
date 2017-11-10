# Ansible role Postfix
Ansible Role for setup and manage Postfix

## Requirements
Ansible version => 2.3

# Vars
## Default role variables
```yaml
admin_email: ''
```
## Example Playbook
```yaml
---
- hosts: all
  roles:
    - postfix
```
# Playbook run
## For all hosts
```
ansible-playbook -i production playbooks/postfix.yml
```
## For single host
```
ansible-playbook -i develop playbooks/postfix.yml --limit backend-01
```
