# ssh_access_revoke
Add and revoke ssh access to instances Automation

**To Give access**
```
ansible-playbook -e "action=grant" main.yml -u root
```

**To Remove Access**
```
ansible-playbook -e "action=revoke" main.yml -u root
```
In **main.yml** instead of hardcoading key you can privde keyfile `(id_rsa.pub)` as well.
