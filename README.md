Apigee OPDK Update Component Inplace
=========

This repository contains an Ansible role to update an Apigee Component inplace. This is not a version upgrade but instead the application of a minor version update.

Requirements
------------

None

Role Variables
--------------


| Variable Name | Description |
| --- | --- |
| component | The component name to use with apigee-service {{ component }} update |


Dependencies
------------

None 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: apigee-opdk-update-component-inplace }

License
-------

Apache 2.0

Author Information
------------------

Carlos Frias

