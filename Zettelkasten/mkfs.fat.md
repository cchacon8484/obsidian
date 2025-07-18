#linux
Manual: https://man7.org/linux/man-pages/man8/mkfs.fat.8.html

mkfs is used to create [[FAT (File Allocation Table )]] file systems on a device or in an image file.
Example of use
```console
mkfs.fat -F32 /dev/nvme0n1p1
```
where *-F32* creates a FAT32 file system and */dev/nvme0n1p1* is the device or image where the FAT system will be created