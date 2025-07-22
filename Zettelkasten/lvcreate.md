#linux 
lvcreate creates a logical volume in an already existing volume group 
manual: https://linux.die.net/man/8/lvcreate
```console
lvcreate -L 30GB volgroup0 -n lv_root
```

where *-L* is to put the size of the volume and *-n* is to specify the name