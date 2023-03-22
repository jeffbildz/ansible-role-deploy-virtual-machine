# ansible-role-deploy-virtual-machine 

This role deploys a KVM image to a VM host 

## Requirements

## Role Variables

```yml
base_image_name: Fedora-Cloud-Base-34-1.2.x86_64.qcow2
base_image_url: https://download.fedoraproject.org/pub/fedora/linux/releases/34/Cloud/x86_64/images/{{ base_image_name }}
base_image_sha: b9b621b26725ba95442d9a56cbaa054784e0779a9522ec6eafff07c6e6f717ea

libvirt_pool_dir: "/var/lib/libvirt/images"

vm_name: f34-dev
vm_vcpus: 2
vm_ram_mb: 2048
vm_net: default
vm_root_pass: test123

cleanup_tmp: no

ssh_key: /root/.ssh/id_rsa.pub
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
