# ansible
Ansible scripts

# docker_install_deb.yml

install docker on Debian

vars: dockeruser - 
non-root user for docker

example:

ansible-playbook docker_install_deb.yml -e "inventory_hostname=192.168.15.15"

