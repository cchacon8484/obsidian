#linux 
FDISK is a tool to create partitions in [[Linux]], also is used to review, resize and delete partitions
Commands:
> m: Displays the help menu, listing all available commands. 
> p: Prints the current partition table of the disk. 
> n: Adds a new partition. You'll then be prompted to choose between primary or extended, and then specify the partition number and size. 
> d: Deletes a partition. You'll be prompted to select which partition to delete. 
> t: Changes a partition's system ID (type). You'll be prompted to enter the partition number and then the system ID for that partition. 
> w: Writes the changes made to the partition table to the disk and exits fdisk. 
> q: Quits fdisk without saving any changes. 
> a: Toggles the bootable flag on a partition. 
> l: Lists known partition types. 