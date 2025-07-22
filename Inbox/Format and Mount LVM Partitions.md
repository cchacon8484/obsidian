We are going to focus in lv_root and lv_home so we need to give [[ext4]] extension
Steps:
1. For lv_root run
```console
mkfs.ext4 /dev/volgroup0/lv_root
```
 2. For lv_home run
```console
mkfs.ext4 /dev/volgroup0/lv_home
```
3. First we need to use the command [[mkdir]] to create our boot directory
```console
mkdir /mnt/boot
```
4. Then we're going to mount our lv_root in the created directory with the command [[mount]] 
```console
mount /dev/nvme0n1p2 /mnt/boot
```
5. Now we're going to create the home directory
```console
mkdir /mnt/home
```
6. And finally we're going to mount lv_home with [[mount]]
```console
mount /dev/volgroup0/lv_home /mnt/home
```
