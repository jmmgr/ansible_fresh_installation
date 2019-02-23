Role Name
=========

This will install some defaults settings for terminal.
Such as tmux, zsh, oh-my-zsh, fzf, etc
As well get the dot files and create the user provided if it doesn't exists

Requirements
------------

NA

Role Variables
--------------

NA

Example Playbook
----------------

Example 

- hosts: all
  roles:
    - role: terminal
      users:
        - username: jesus
          group: root

License
-------

BSD

Author Information
------------------

Jesus
