#linux
After [[Install base ARCH Linux package]] you need to generate an [[fstab file]] for this we're going to use [[genfstab]] 
```console
genfstab -U -p /mnt >> /mnt/etc/fstab
```

Where *-U* use [[UUID (Universally Unique Identifier)]] instead of device names, this because the device names can change but the UUID not this make it more reliable; *-p* to use [[POSIX (Portable Operating System Interface)]] output format to ensure compatibility; */mnt* the path where the system is mounted; *>> /mnt/etc/fstab* to append the output to the path in the new system