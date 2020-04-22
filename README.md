# Capstone Project Intro

This is my Udacity Cloud DevOps Capstone project. In this project I created a CI/CD pipeline for a basic website which will be deployed to a cluster in AWS Kops

## Prerequisites

To be able to use this CI/CD pipeline we will need:
- Jenkins
- kops
- Ansible
- Vagrant

1. To install Jenkins please follow this guide http://jenkins.io/doc/book/installing/
2. To install Vagrant please follow this guide https://www.vagrantup.com/downloads.html


### 1. Create AWS Cops clusters Using Vagrant

You can follow **ReadMe** file in **Vagrant-Kops-Ansible** Directory To Install AWS Kops Cluster Using Vagrant and Ansible.

### 2. Set up Jenkins EC2 Instace.

You Can Launch EC2 Instance to Install Jenkins, Add **BlueOcean** Plugin and **Kubernetes Continuous Deploy** Plugin and **Your Docker Hub** Credentials and **kubeconfig** Credentials.

### 3. Build Pipeline

Build my simple code of NGINX web page, Lint it, use the Aqua SecurityScanner to scan the code, build the html artifcat and upload it to AWS S3

### 3. Deploy Blue/Green pipelines

Deploy the web app to blue deployment instances then to the green one
