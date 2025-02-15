# Ansible Configuration Management Project

## Project Overview
This project aims to automate the configuration of two server groups using Ansible: one for Apache and another for Nginx. Additionally, it includes the installation of Java on the Apache server group after the Apache configuration is complete. This setup ensures efficient management and deployment of server configurations, adhering to best practices in DevOps.

## Features

1. **Server Group Configuration**:
    - **Apache Server Group**: Installs Apache HTTP Server, deploys an HTML file with server information, starts the Apache service, and sends a post-installation message.
    - **Nginx Server Group**: Installs Nginx HTTP Server, deploys an HTML file with server information, starts the Nginx service, and sends a post-installation message.

2. **Java Installation**:
    - Installs Java on the Apache server group using Ansible roles in a dedicated 
