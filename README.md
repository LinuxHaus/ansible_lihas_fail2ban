ansible_lihas_fail2ban
=========

Configures fail2ban for debian servers.

- installs fail2ban
- set journald default source
- set journald logtarget
- configure ssh
- set timer for timeout
- sets ignore ip adresses
- if apache2 is installed, configuring it

Requirements
------------

To run solo:

>ansible-galaxy install -r requirements.yml
>
>ansible-playbook -i localhost, fail2ban.yml

Dependencies
------------
lihas_variables

Example Playbook
----------------

>---
>- hosts: '*'
>  role: lihas_common
>...

License
-------
GNU General Public License v3.0
