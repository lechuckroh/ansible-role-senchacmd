Ansible role: Sencha CMD installer
=========

Requirements
------------

Ubuntu target server

Role Variables
--------------

senchacmd/defaults/main.yml
  - senchacmd_version

Example Playbook
----------------
$ansible-galaxy install choijero.sencha_cmd_installer

    - name: sencha cmd
      hosts: all
      become: true
      roles:
        - sencha_cmd_installer


Author Information
------------------
choijae0@gmail.com
