# Site-Deployment-using-AWS-Terraform-and-Ansible
Site Deployed with AWS, Terraform, and Ansible

SETUP

*Created Ubuntu 16 server
*Using Python 2.7.12 until Ansible offers smoother support for Python 3
*apt-get update
*apt-install python pip
*pip install --upgrade pip (Note: 9.0.1)
*downloaded Terraform 0.11.2 with curl
*mkdir /bin/terraform and unzipped
*export PATH=$PATH:/bin/terraform
*pip install awscli --upgrade
*apt-add-repository ppa:ansible/ansible
*apt-get update
*apt-get install ansible
*ssh-keygen
*ssh-add -l
*disabled host key checking
*mkdir terransible
