# Ansible role `sencha-cmd`

An ansible role for sencha-cmd

Tested under:
* CentOS 7.4

## Requirements

No requirements

## Role Variables

| Variable               | Default                 | Comments                   |
|:-----------------------|:------------------------|:---------------------------|
| `senchacmd_version`    | `6.6.0.13`               | sencha-cmd version         |

## Dependencies

No dependencies

## Example Playbook

```yaml
---
- name: example
  hosts: all
  become: true
  vars:
    senchacmd_version: 6.6.0.13
  roles:
  - lechuckroh.senchacmd
```

## License
MIT
