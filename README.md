WebLogic
=========
Playbook that install a WebLogic service in a Linux environment. Provides the start and stop features.

Dev Status
-------

Finished

Requirements
------------
*For windows OS is a must a previous configuration to running Ansible
* [Prepare Windows machine for Ansible](https://docs.ansible.com/ansible/latest/user_guide/windows_setup.html): Be sure to prepare the correct environment and the previous requirements.

*Java JDK version 1.8 
*Oracle weblogic 12C

Role Variables
--------------

The variables used are:
* START
* STOP

Each variable represents the function that the role will execute.

Dependencies
------------

* [Ansible Windows Modules](https://galaxy.ansible.com/ansible/windows): Older ansible versions may need the manual install of the windows modules.
* [Oracle Weblogic server] https://www.oracle.com/middleware/technologies/weblogic-server-installers-downloads.html : Version 12c
