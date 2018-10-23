[![License](https://img.shields.io/github/license/zicklam/ansible-oracle-client.svg?style=flat)](LICENSE)
![Github Downloads](https://img.shields.io/github/downloads/zicklam/ansible-oracle-client/total.svg?style=popout)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-zicklam.oracle_client-30677.svg?style=flat)](https://galaxy.ansible.com/zicklam/oracle_client)


Ansible Playbook for Oracle Runtime Client (v12.2.0) installation
=================================================================

Requirements
------------

There aren't many requirements. Currently the scripts are only tested on following environments:
* CentOS 7 or RHEL 7 (x86_64)
* CentOS 6 or RHEL 6 (x86_64)
* Ansible 2.5

I worked for the dependencies only with the yum_module so far. On other distributions this role may need some extension.

Role Variables
--------------


Example Playbook
----------------

`$ ansible-playbook -i <inventory-file> site.yml`


License
-------
MIT


Author Information
------------------

This role was creaded by [zicklam](github.com/zicklam)
