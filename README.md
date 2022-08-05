## Ansible LEMP 
---
versions:
> nginx: latest
> php: 7.4
> mariadb: latest
> CentOS versions: 7 

## Run on CentOS 7
---
It requires to have CentOs 7 with ansible and python3 already installed.

## Run playbook locally
```
ansible-playbook --connection=local lemp.yml
```

