# NOT_COMPLETED DigitalOcean Website with HTTPS certificate

## Specifications

macOS: Sonoma 14.2.1

Ubuntu: ubuntu-20-04-x64

## INSTRUCTIONS

1. Add your machine SSH to DigitalOcean account

2. Create API token and add to your DigitalOcean project

3. Update vars files to your personal preferences

   a) Update u_token in vars/keys.yml (api_token)
   
   b) Update u_ssh in vars/keys.yml (ssh fingerprint)

   c) Update domain / user preferences in inventory and vars/main.yml

   d) Update file location of hosts_dest in vars/keys

## Droplet Delete

   If you would like to delete droplets, simply switch state of "Provision Digitalocean droplets" from PRESENT to ABSENT and run playbook.

## Links 

   https://github.com/geerlingguy/ansible-for-devops/tree/master/lamp-infrastructure

   2nd edition of Ansible for DevOps Jeff Geerling
