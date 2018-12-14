# Ansible fresh installation 

### For a virtual machine

Get the host
```
ip address | grep inet
```

Add it in the hosts file

### local

Install ansible and add ```localhost``` in the hosts file

## Run 
```
ansible-playbook install.yml -i hosts -u root -k -vvv
```
