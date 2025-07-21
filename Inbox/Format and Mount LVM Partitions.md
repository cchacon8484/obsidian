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
3. [[Mount partition]] 