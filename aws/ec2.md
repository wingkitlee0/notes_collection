
### Check EBS volumes

#### List the volumes
```
lsblk
```

#### Check if the volume is formatted

```
sudo file -s /dev/xvdf
```

#### Mount 

```
mkdir new_directory
sudo mount /dev/xvdf new_directory
```