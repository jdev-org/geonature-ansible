# geonature-ansible

Ansible scripts for the installation of Géonature.

## Supported operating systems
* Ubuntu 18.04 LTS
* Ubuntu 20.04 LTS
* Debian 9
* Debian 10

## Instructions

1. Install Ansible
[Ubuntu](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu)
[Debian](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-debian)

2. Run playbook
`ansible-playbook ./install.yml`

NB: Do not run with sudo. You will be asked to enter the password necessary for sudo permissions.
