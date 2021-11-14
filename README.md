rnp-tools-ansibleroles-mikrotik-setidentity
=========

Ansible Role - Mikrotik - Set Identity

![Overwiew](https://gitlab.com/rachuna-net.pl/tools/ansibleroles/mikrotik/rnp-tools-ansibleroles-mikrotik-setidentity/-/raw/develop/docs/setidentity.png)

Role Variables
--------------

Defaults role values:

```yaml
input_role_ansible_host:             "{{ ansible_host }}"
```

Example Playbook
----------------

```yaml
- hosts: all
  gather_facts: yes
  tasks:

  - include_role:
      name: rnp-tools-ansibleroles-mikrotik-setidentity
    vars:
      input_role_ansible_host:              "{{ ansible_host }}"
```

License
-------

BSD 3-Clause

Author Information
------------------

### Maciej Rachuna
SysOps/DevOps