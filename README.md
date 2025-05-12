lighthouse
=========

This role can install and configure Lighthouse

Requirements
------------



Role Variables
--------------



Dependencies
------------

none

Example Playbook
----------------

---
- name: Install and configure Vector  
  hosts: your's hostname  
  become: true  
  roles:  
    - { role: lighthouse, vector_version: "latest"}

if you use req.yml

- name: Install and configure Vector  
  hosts: your's hostname  
  gather_facts: true  
  roles:  
    - lighthouse


License
-------

MIT

Author Information
------------------

Mikhail Bladurin for Netology