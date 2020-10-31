hashmicro-test
=============

Prerequisites
-------------
* It requires to configure ansible hosts and ssh keys to connect to instaces 
* Config file can be configured either in `/etc/ansible/hosts` or creating new inventory file

Run playbook, run with this command :
-------------------------------------
`ansible-playbook playbook.yml`

**if inventory file is configured in a new file then run this command instead :**  
`ansible-playbook -i <inventory_file_path> playbook.yml`
