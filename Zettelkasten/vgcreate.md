#linux 
This command creates a [[Volume Group]]
manual: https://linux.die.net/man/8/vgcreate
Usage: 
```console
vgcreate volgroup0 /dev/mapper/lvm
```

where *volgroup0* is the name of the [[Volume Group]] and */dev/mapper/lvm* is the path of the desired location for the [[Volume Group]] the lvm is an disk partition created before with [[pvcreate]]
