# Check Disk Usage using Ansible

## How To Use
1. Create your hosts
2. Edit variable want to use in `disk_avail.yml` file
3. Run ansible playbook
```
$ ansible-playbook disk_use%.yml -i hosts
```

4. Check debug log at disk_usage.txt
```
$ cat disk_usage.txt
``` 





# Check available disk
```
$ ansible-playbook disk_avail.yml -i hosts
```
