# ansible-auditbeat

An Ansible role for installing and configuring AuditBeat

## Sysmon Configuration

The role applies an [AuditD ruleset](https://github.com/bfuzzy/auditd-attack) based on the MITRE Att&ck framework.

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook, add the code below:

```
- name: Install AuditBeat
  import_role:
    name: ansible-auditbeat
```

## Disclaimer

This role is for use in the SANS 699 course and is provided as is.

## License

MIT / BSD