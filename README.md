# pzzl / Puzzler

Setup the localhost with Ansible.

```shell
$ cd .../ansible
```

```shell
$ ansible-playbook --ask-vault-password setup.yml -t desktop
Vault password: 

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
