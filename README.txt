Jacob Smith
CSEC 473

Ansible Playbook for configuring sql servers

- main.yml
  - playbook
  - installs mysql and dependencies
  - starts mysql
  - creates users
  - creates gray table
  - copies .sql file from control node to target machine
  - imports .sql into mysql

- inventory.ini
  - contains hosts

- ansible.cfg
  - defines inventory file

- .my.cnf
  - special file meant to set root password during setup

- gray.sql
  - sql file to create database


GRAY TEAM SCORING PASSOWORD:

user: grayteam
password: grayteam


