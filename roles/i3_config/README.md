Role Name
=========

We will add all the i3 configuration package.

We will be based in Manjaro I3 version, to configurate it.

Requirements
------------

You need to i3 installed, we will use the version of Manjaro as starting point.

As well need to install firsts the Role terminal (we need the dot files at the momnet)

Role Variables
--------------

NA

Dependencies
------------

NA

Example Playbook
----------------

Example

- hosts: all
  roles:
    - role: i3
      users:
        - username: jesus
          group: root

License
-------

BSD

Author Information
------------------

Jesus
