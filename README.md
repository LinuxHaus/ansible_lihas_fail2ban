ansible_lihas_fail2ban
=========

Configures fail2ban for debian servers.

- set journald default source
- set journald logtarget
- configure for ssh
- if apache2 is installed, configuring for it

Requirements
------------

To run solo:

ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, fail2ban.yml

Dependencies
------------
-


License
-------
GNU General Public License v3.0
