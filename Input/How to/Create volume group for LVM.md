To create a [[Volume Group]]  for [[LVM (Logical Volume Manager)]] we're going to use [[vgcreate]]  
```console
vgcreate volgroup0 /dev/mapper/lvm
```

Where *volgroup0* is the name of the [[Volume Group]] and */dev/mapper/lvm* is the path we are using for LVM