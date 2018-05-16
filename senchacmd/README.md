Ansible role: Sencha CMD installer
=========

Requirements
------------

Ubuntu target server

Role Variables
--------------

- nchacmd/defaults/main.yml
senchacmd_version

Example Playbook
----------------

    - name: sencha cmd
      hosts: all
      become: true
      roles:
        - senchacmd


Author Information
------------------
choijae0@gmail.com