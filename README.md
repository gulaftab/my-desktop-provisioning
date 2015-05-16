My Desktop/Laptop Provisioning
===============================

Ansible provisioning to manage my personal Ubuntu desktop.

Roles list
--------------

- Common (Essentials packages like vim, git etc)
- latex ( using https://github.com/marklee77/ansible-role-latex 

Running
--------
ansible-playbook -i hosts -K setup.yml
