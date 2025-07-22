#linux 
We need to prepare three partitions for boot partition, [[LVM (Logical Volume Manager)]], and one for the Linux system. 
Steps to prepare the hard drive for the [[Install ARCH Linux]]
1. We need to create three partitions for Linux, we can follow the guide [[Create partitions on Linux]] to accomplish this
2. Create the first partition with 1 GB for [[EFI System partition (ESP)]] 
3. Create the second partition with 1 GB for the [[Boot partition]] 
4. Create the third partition with the rest of the size for the [[Linux]] installation, for this we will use [[LVM (Logical Volume Manager)]] for this should use additional settings for [[Create partition for LVM]] 
5. Now with the partitions created we will need to [[Format the partitions for Linux installation]]
6. We need to [[Encrypt Partition]] the third partition before the format
7. And then we need to [[Open the encrypt partition]] 