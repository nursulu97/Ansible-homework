# Ansible-homework
```

PLAY [all] ***********************************************************************************************

TASK [Gathering Facts] ***********************************************************************************
ok: [64.23.244.221]

TASK [Install required packages] *************************************************************************
[DEPRECATION WARNING]: Invoking "apt" only once while using a loop via squash_actions is deprecated. 
Instead of using a loop to supply multiple items and specifying `name: "{{ item }}"`, please use `name: 
['apache2', 'tree', 'git']` and remove the loop. This feature will be removed in version 2.11. 
Deprecation warnings can be disabled by setting deprecation_warnings=False in ansible.cfg.
ok: [64.23.244.221] => (item=[u'apache2', u'tree', u'git'])

TASK [Start Apache service and enable it] ****************************************************************
ok: [64.23.244.221]

TASK [Create group 'kaizen'] *****************************************************************************
ok: [64.23.244.221]

TASK [Create group 'devops'] *****************************************************************************
ok: [64.23.244.221]

TASK [Create group 'qa'] *********************************************************************************
ok: [64.23.244.221]

TASK [Add the user 'tester' to the group 'qa'] ***********************************************************
ok: [64.23.244.221]

TASK [Add the user @Nursulu07 , appending the group 'qa' and 'kaizen' to the user's groups] **************
ok: [64.23.244.221]

TASK [Copy files from Homework1 to remote machine] *******************************************************
ok: [64.23.244.221]

PLAY RECAP ***********************************************************************************************
64.23.244.221              : ok=9    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0   



root@ubuntu:~# ls
main.yml  snap
 ```
