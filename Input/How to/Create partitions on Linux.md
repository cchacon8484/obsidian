#linux
1. Identify the device 
```console
lsbk
```
2. Open [[FDISK]]  (nvme0n1 should be changed to your desired device)
```console
fdisk nvme0n1
```
3. Print the partitions
```console
p
```
4. Empty the partition table 
```console
g
```
5. Create the new partition
```console
n
```
6. Select the default
```console
1
```
7. Leave the first sector as it is (just hit enter)
8. Select the size (for this example will be 1 GB)
```console
+1G
```
