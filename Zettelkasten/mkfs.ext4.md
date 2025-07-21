#linux 
Is a [[Linux]] used to create an [[ext4]] file system on a device storage device or partition, use a retarded assignation “Allocate on flush” this improves the performance and reduce the fragmentation. 
Example of use:
```console
mkfs.ext4 /dev/nvme0n1p2
```

where */dev/nvme0n1p2* is the device or image to make the partition