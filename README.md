Ansible role: Sencha CMD installer
=========

Requirements
------------

Ubuntu target server

Role Variables
--------------

senchacmd/defaults/main.yml
  - senchacmd_version: "6.5.3.6" (default)

Example Playbook
----------------
$ansible-galaxy install choijero.sencha_cmd_installer

    - name: sencha cmd
      hosts: all
      become: true
      vars:
        senchacmd_version: "6.2.2" (optional)
      roles:
        - choijero.sencha_cmd_installer


Author Information
------------------
choijae0@gmail.com
