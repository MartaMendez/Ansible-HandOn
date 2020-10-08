# Website deployment project
Ansible project to deploy a website on a remote server. 

## Pre requisites
1) At least three connected hosts:
    * one with ansible
    * two remotes:
         - database server
         - web server

2) Website code available in github

3) To set up the database server, the following should be defined:
    * databases to create
    * users to access those databases and their passwords
    * sql file to create tables and load database

4) To set up the web server, the following should be defined:
    * databases to access
    * users to access those databases and their passwords
    * sql file to create tables and load database

## Run
