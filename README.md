# Website deployment project
Ansible playbook to deploy a website on a remote server. 

## Pre requisites
1) At least three connected hosts:
    * one local server
    * two remotes servers:
         - database server
         - web server
2) [Install ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installation-guide) on the local host

3) To set up the database server, the following should be defined:
    * databases to create
    * users to access those databases and their passwords
    * sql file to create tables and load database

4) To set up the web server, the following should be defined:
    * databases to access
    * users to access those databases and their passwords
    * sql file to create tables and load database

## Run
```bash
ansible-playbook playbook.yml -i inventory.txt
```
