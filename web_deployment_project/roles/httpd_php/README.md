# httpd_php role
This role installs, starts and enables and HTTP PHP server and sets up a website.
It creates also creates connection to a db server.

## Notes
* httpd.conf file is set for Centos7 and index.php configuration.
* The following variables must be set in playbook:
  - web git repository path
  - databa server host
  - database server db_port
  - mysql database to access
  - mysql user to access and its password
