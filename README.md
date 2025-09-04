# Ansible Install Helm
Script for installing and configuring helm in Ansible

## Example

```yaml
- hosts: all
  become: true
  vars:
    arch_type: "arm64"
    
  tasks:
    - name: Install Helm
      include_tasks: ./task/ansible_install_helm/playbook.yml 
```