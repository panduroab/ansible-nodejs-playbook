# Ansible
Ansible is the simplest way to automate apps and IT infrastructure. Application Deployment + Configuration Management + Continuous Delivery.

#### Description
Ansible Playbook to install Git, Node.js, NPM, MongoDB, PM2 and Nginx.

###Details
This PlayBook works with Ubuntu 14.04.5 LTS (Trusty Tahr) and Python 2.7

#### How to use it
1.- Install Ansible on your machine: http://docs.ansible.com/ansible/intro_installation.html

2.- Update `hosts` file to add your remote server host.

3.- Replace `my_remote_user` with your remote user on `main.yml` file.

4.- Run this command in your local machine:
```
ansible-playbook -i hosts main.yml --ask-become-pass
```