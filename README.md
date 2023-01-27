# Ansible_LAMP_stack_On_Debian_10

This repo is going to deploy LAMP + Wordpress web stack with Ansible. With phpMyAdmin, you can manage the database via the web UI.
It is fully automated and feel free to try :)


Since this repo is for the demo purposes, please download PHP with the latest version (currently ver. 8.2) and store all the credentials with either Ansible Vault or in the background.

There is a default page (index.html) in the directory, if you do not want to have it, just remove the task (copy the template file to be index.html) in full.yml.


You can run the following command to deploy the LAMP stack on Debian 10

Please update the host inventory for your Virtual machine IP

```
ansible-playbook -i hosts.yml playbook/full.yml
```
