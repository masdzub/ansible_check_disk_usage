# Check Disk Usage using Ansible

## How To Use
1. Create your hosts
2. Edit variable want to use in `check_disk.yml` file
3. Run ansible playbook
```
$ ansible-playbook check_disk.yml -i host
```

4. Check debug log at disk.txt
```
$ cat disk.txt
``` 
