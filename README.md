# CloudFormation-Ansible-Static-Website
> **CloudFormation** is a fantastic tool for automatically _provisioning your infrastructure_, it can be used in conjunction with other software such as **Ansible** to deploy applications.

![AWSandANSIBLE](/images/ansible-cloudformation.png) 

## Step-by-Step Guide

1. Clone the GitHub Repo

        git clone https://github.com/mrbilalshafiq/CloudFormation-Ansible-Static-Website

2. Install AWSCLI, Ansible, Python3, & Pip3:

        bash install.sh

3. Configure AWSCLI with your Credentials:
    
        aws configure

4. Run the Ansible Playbook

        ansible-playbook create.yaml
        
5. Clean Up

        ansible-playbook delete.yaml
