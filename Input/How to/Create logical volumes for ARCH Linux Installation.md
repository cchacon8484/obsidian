To create logical volumes for [[ARCH Linux Installation]] we need to use [[lvcreate]]
for the first volume we are going to assign 30gb for the [[ARCH Linux Installation]]

```console
lvcreate -L 30GB volgroup0 -n lv_root
```

Then we are going to create a separated logical volume for the user data, this is handy in case that we need to reinstall our [[Linux]] 

```console
lvcreate -L 250GB volgroup0 -n lv_home
```

This 250 GB depends on your HD