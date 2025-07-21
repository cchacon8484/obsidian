To initialize partitions for [[LVM (Logical Volume Manager)]] we need to use [[pvcreate]]
```console
pvcreate /dev/mapper/lvm
```
*/dev/mapper/lvm* reference to the  open volume (the third partition)