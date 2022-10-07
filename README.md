# ans-nginx
This ansible will will install nginx server.
Kindly setup passwordless authentication before using this ansible role using below instructions

1) Generate ssh key
ssh-keygen -t rsa -b 2048 -v
2) copy public key to all client VMs
ssh-copy-id -i ~/identity.pub waqas@10.4.3.10
3) Now you use ssh private wile running ansible playbook
