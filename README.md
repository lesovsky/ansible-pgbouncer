### README: install-pgbouncer

#### Features:
- supported distributions: Redhat 6, CentOS 6, Scientific Linux 6, Oracle Linux.
- allow specify pools, allowed users and other pgbouncer settings.
- supported only md5, any or trust auth types.
- add logrotate config

#### Known issues:
- plain and crypt auth types does not implemented and not tested.

#### Todo:

#### How-to use:
- download repo with git clone;
- cd into role directory;
- change hosts: variable in role.yml;
- start ansible-playbook with role.yml and your inventory file.
```
ansible-playbook -i /etc/ansible/staging role.yml
```
