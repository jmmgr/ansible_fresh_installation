# Ansible fresh installation 

### For a virtual machine

Get the host
```
ip address | grep inet
```

Add it in the hosts file

### local

Install ansible
add ```localhost``` as the host

## Run 
```
ansible-playbook install.yml -i hosts -u root -k -vvv
```
