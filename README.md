# MySQL Replication and Percona Monitoring system

- [Ansible doc](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- [MySQL doc](https://dev.mysql.com/doc/refman/8.0/en/replication.html)

## Roles
- [x] MySQL 
- [x] MySQL Exporter



## Setup
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run
Add ssh config hostname to `hosts`
```
ansible-playbook setup.yml
```
