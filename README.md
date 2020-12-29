Ansible-playbook. Deploying image to openstack and creating an instance with users, ssh-keys and repositories.

Launch:

ansible-playbook deploy-openstack.yml --ask-vault-pass

password: devops

###########################################################################

Notes:
root@ds:/home/user# ifconfig br-ex 172.24.4.1 netmask 255.255.255.0
root@ds:/home/user# ifconfig br-ex up
root@ds:/home/user# route add  -net 172.24.4.0 netmask 255.255.255.0 br-ex
