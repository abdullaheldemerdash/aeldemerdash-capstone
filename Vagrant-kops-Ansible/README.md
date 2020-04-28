# vagrant-kops-ansible

This repository contains the tools for deploying Kubernetes cluster in Amazon AWS using the Kops tool by Ansible Playbook inside Centos 7 Vagrant machine.


1. Install Vagrant and VirtualBox in you machine.

https://www.vagrantup.com/downloads.html

https://www.virtualbox.org/wiki/Downloads


2. Access your AWS account from console and create The following 

-IAM user with Admin permission "save your secrect key and access key"

-Add "Hosted zone" by Route53 service to add your domain.



3. Clone The repo to  your Local Machine : https://github.com/aeldemerdash-capstone/vagrant-kops-ansible 

-Change The following  Vars to match your infrastructure in "group_vars/all" [Access Key - Secret Key - Bucket Name - cluster_name - DNS Zones]

-In repo and launch the Vagrantfile through these commands :"vagrant init"  then "vagrant up"

-ssh to vagrant machine through this command : "vagrant ssh"
