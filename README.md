evergreenils-ncip
=========

This role installs the NCIPServer git code and configures it for Evergreen.

Requirements
------------

This role presumes you have a working evergreen and openils install as that is required for installation of NCIP. 

Role Variables
--------------


Example Playbook
----------------

    - hosts: evergreen-app-servers
      roles:
         - { role: aadl.evergreenils-ncip }

License
-------

GPLv3 
