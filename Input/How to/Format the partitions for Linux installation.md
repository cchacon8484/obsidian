#linux 
To format the partitions in [[Linux]] we use embedded program to do it for the EFI we're going to use [[mkfs.fat]]
```console
mkfs.fat -F32 /dev/nvme0n1p1
```

For the boot partition we're going to use [[mkfs.ext4]]

```console
mkfs.ext4 /dev/nvme0n1p2
```

