Ansible-Role-Example
=========

This is just a example of how to use and configure the Ansible Galaxy - See http://www.beyeler.com.br/2017/03/conhecendo-um-pouco-do-ansible-galaxy/

Dependencies
------------

lucascbeyeler.commons - Default playbook to prepare you environment to receive any kind of service

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: lucascbeyeler.role-example

Result
-------
```
PLAY [all] *********************************************************************

TASK [setup] *******************************************************************
ok: [192.168.0.19]

TASK [lucascbeyeler.role-example : debug] **************************************
ok: [192.168.0.19] => {
    "msg": "For a moment, nothing happened."
}

TASK [lucascbeyeler.role-example : debug] **************************************
ok: [192.168.0.19] => {
    "msg": "Then, after a second or so, nothing continued to happen."
}

PLAY RECAP *********************************************************************
192.168.0.19               : ok=3    changed=0    unreachable=0    failed=0   
```

License
-------

GPLv3

Author Information
------------------

