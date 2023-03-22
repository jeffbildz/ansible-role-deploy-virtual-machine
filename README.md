# ansible-role-deploy-virtual-machine 

This role deploys a KVM image to a VM host 

## Requirements

## Role Variables

```yml
---
# defaults file for ansible-role-common

# Variables for Configurations
common_dns_suffixes: "lemus.int,bilder.int"

common_hostname: "{{ ansible_hostname }}"
common_time_zone: Central Standard Time

common_7zip_status: present
common_7zip_version: 22.1

common_npp_status: present
common_npp_version: 8.4.4

common_powershell_core_status: present
common_powershell_core_version: 7.2.5

common_sysinternals_status: latest
common_sysinternals_version:
```

## Dependencies

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - deploy-virtual-machine 
```

## License

BSD

## Author Information

Contributors:

- Jeff Bilder

Please consider contributing back to this project. https://github.com/jeffbildz/ansible-role-deploy-virtual-machine
