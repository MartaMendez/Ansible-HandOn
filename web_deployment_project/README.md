# web_deployment_project
This project deploys a website. It sets up a database server and a web server.

## Pre requisites
1) At least three connected hosts:
    * the one where ansible is installed
    * two remotes:
      - database server
      - web server

2) Website code available in github

3) Regarding database server, the following should be defined:
    * databases to create
    * users to access those databases and their passwords
    * sql file in order to create tables and load database

4) Regarding web server, the following should be defined:
        * databases to access
        * users to access those databases and their passwords
        * sql file in order to create tables and load database
