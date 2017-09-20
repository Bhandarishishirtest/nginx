nginx
=========

This role installs epel repository on Cetos7.X & Redhat 7.X, and then  installs  nginx in the webserver. 
Role nginx also deploys required configuration and webpage to the nginx server. 

Requirements
------------
A working server (Centos 7.X / Redhat 7.X). 
Have host entries of web server in controller host.
Have key based authentication or password for the webserver for SSH. 

Playbook test environemt:
----------------
    - hosts: localhost # This role was tested in localhost and in a server in ad-hoc environemt. 

