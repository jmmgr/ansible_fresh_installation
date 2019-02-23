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

For installing terminal and i3_config we can do:
```
ansible-playbook install.yml -i hosts -u root -k -vvv
```

For flatpak once you have created the jesus user, you can run
```
ansible-playbook install.yml -i hosts -u jesus -b -k -K -vvv
```

with ```-b``` will become sudo, and ```-K``` will request the sudo password.
