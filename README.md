# Website deployment project
Ansible playbook to deploy a website on a remote server. 

## Pre requisites
1) At least three connected hosts (CentOS7):
    * one local server
    * two remotes servers:
         - database server (mariaDB)
         - web server (PHP)
2) [Install ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installation-guide) on the local host

3) To set up the database server, the following should be defined:
    * database to create
    * users to access those databases and their passwords
    * sql file to create tables and load database

4) To set up the web server, the following should be defined:
    * database to access
    * users to access those databases and their passwords
    * sql file to create tables and load database

5) Website code on a git repo.

## Setup

## Run
```bash
ansible-playbook playbook.yml -i inventory.txt
```
