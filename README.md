# ansible
Ansible playbooks

## docker_install_deb.yml

install docker on Debian

vars: dockeruser - 
non-root user for docker

example:

ansible-playbook docker_install_deb.yml -e "inventory_hostname=192.168.15.15"<br>
or<br>
ansible-playbook docker_install_deb.yml -e "inventory_hostname=docker_hosts"

