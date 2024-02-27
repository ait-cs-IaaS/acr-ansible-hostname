# Ansible-Role: acr-ansible-hostname

AIT-CyberRange: Manages client hostname. 


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
hostname: localhost

```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - acr-ansible-hostname
      vars:
        hostname: "newhostname"
```

## License

GPL-3.0

## Author

- Lenhard Reuter