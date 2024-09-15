# Docker Compose Installation Guide
This guide provides instructions for installing Docker Compose on Amazon Linux and Ubuntu systems.

## Amazon Linux
Follow the steps below to install Docker Compose on Amazon Linux:

1.  Update the system packages:
    `sudo su`
    `yum update`

2.  Download the installation script:
    `wget -O install.sh https://raw.githubusercontent.com/cloudsecnetwork/training-resources/main/devsecops/docker-compose-install.sh`

3.  Make the script executable:
    `chmod +x install.sh`
    
4.  Run the installation script:
    `./install.sh` 

## Ubuntu
Follow the steps below to install Docker Compose on Ubuntu:

1.  Download the latest version of Docker Compose:
    `curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose` 
    
2.  Make Docker Compose executable:
    `chmod +x /usr/local/bin/docker-compose` 
  
3.  Verify the installation by checking the version:
    `docker-compose --version`
