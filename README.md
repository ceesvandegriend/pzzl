# pzzl / Puzzler

Setup the localhost with Ansible.

```shell
$ cd .../src/nsible
```

```shell
$ ansible-playbook --ask-become-pass --ask-vault-password setup.yml -t desktop
BECOME password: ...
Vault password: ...

PLAY [Playing with Ansible] ********************************************************************************************************

TASK [Gathering Facts] *************************************************************************************************************
ok: [localhost]

TASK [common : Apt full-upgrade] ***************************************************************************************************
ok: [localhost]

TASK [common : Install packages] ***************************************************************************************************
ok: [localhost]

TASK [desktop : Install packages] **************************************************************************************************
ok: [localhost]

PLAY RECAP *************************************************************************************************************************
localhost                  : ok=4    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0   

```
