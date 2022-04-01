# pzzl / Puzzler

Setup the localhost with Ansible.

Store ansible-vault password in `~/.pzzl-ansible-vault`.

N.B. Password is in BitWarden as entry `Pzzl Ansible Vault`.


```shell
$ cd .../src/ansible
```

```shell
$ ansible-playbook -K -t desktop setup.yml
BECOME password: ...

PLAY [Playing with Ansible] ********************************************************************************************************
...
```
