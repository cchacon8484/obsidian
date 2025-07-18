#linux 
This encryption is a good to have in our main system partition. 
To encrypt our partition we're going to use [[Cryptsetup]]: 

```console
cryptsetup luksFormat /dev/nvme0n1p3
```

This will initialize an [[LUKS (Linux Unified Key Setup)]] and establish to set a passkey