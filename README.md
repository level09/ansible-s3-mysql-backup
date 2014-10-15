Backup to S3 using Ansible
=========================

Backup mysql database and send it over to S3

Run this using: 

```
ansible-playbook -i hosts backup.yml
```


Requirements:
Python Mysql and boto 

 ```
 apt-get install python-mysqldb
 pip install boto
```
