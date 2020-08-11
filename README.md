   AWX
=========

A simple Ansible role for installing and configuring the Ansible AWX on RHEL/CentOS 8.

Install the necessary packages.


Requirements []
------------

Role Variables
--------------


Variables below are required

| Variable                                     | Default                       | Comments                                     
| :---                                         | :---                          | :---       
|                                              |                               |
| `awx_admin_password:`                        |                               | Inform admin password
|                                              |                               |
| `awx_configure_dns`                          |                               | Inform DNS servers
|                                              |                               |


Dependencies []
------------ 

Example Playbook
----------------
```yml
---
- hosts: awx_server
  become: yes
  roles:
    - awx
...
```

Example inventory
----------------
```yml
[awx_server]

192.168.0.50
```
## Contributing

Issues, feature requests, ideas are appreciated and can be posted in the Issues section.


Author Information
------------------
LinkedIn: https://br.linkedin.com/in/almircandido
