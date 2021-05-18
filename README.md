Ansible Role: supervisor(pkg)
================================================================================
Install and configure supervisor

- Install supervisor using yum at CentOS 7
- Configure /etc/supervisord.conf

Requirements
--------------------------------------------------------------------------------
- Python 2.7

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in defaults/main.yml file.

```yaml
supervisor:
  enabled: true
  started: true
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-supervisor-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

