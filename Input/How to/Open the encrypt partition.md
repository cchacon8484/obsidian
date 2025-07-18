#linux
To open an encrypt volume that was encrypted [[LUKS (Linux Unified Key Setup)]] you need to run:
```console
cryptsetup open --type luks /dev/nvme0n1p3 lvm
```

with this *luks* is the type of encryption, */dev/nvme0n1p3* is the device and *lvm* is the name 