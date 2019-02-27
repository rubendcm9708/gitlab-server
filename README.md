# Local GitLab Server

This repository have all the configuration to set up a local GitLab Server using a virtual machine with Docker. Additionally, I incluide an automated backup system that use the GitLab Backup Service to create a .tar with all the data (repositories, users, groups and projects) and logs, but also downloads the master branch of every repository to a external hard disk connected to the Host Server.

### Implemented Technologies
* VMware Workstation Pro 11  
* Ubuntu Server 18.04   
* Docker and Docker Compose  
* GitLab   
* Crontab for backup automation  
