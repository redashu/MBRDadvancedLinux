# Storage in Linux 

##  Object and block discussion 

<img src="storage.png">

## Story of partition table

<img src="ptable.png">

## steps to partition a new raw hdd

<img src="prules.png">

# creating partition using GPT

<img src="gdiskcreate.png">

## format and mount

<img src="formatm.png">

# Device Mapper

<img src="dm.png">

## LVM concept 

<img src="lvmconcept.png">

## creating Physical volume 

<img src="pvinstall.png">

---
----

## pv create

<img src="pvcreate.png">

##  volume group create 


<img src="vgcreate.png">

## creating logical volume from volume group

<img src="lvcreate.png">

##  formating and mounting 

<img src="lvfm.png">

## LVM extending 

<img src="lvextend.png">

## lvm resizing 

<img src="lvmresize.png">

----

## if XFS is the existing filesystem then 

<img src="xfsgrow.png">

## in case of EXt,2,3,4

```
resize2fs  path of LV 

```

## Extending volume group

<img src="vgextend.png">


# LVM and  hard disk clean process 

## Inshort we can revert usable disk to RAW disk 

## process of lvm remove

<img src="cleanup.png">


# Step of clean up lvm type hard disk 

## Step 1 : take backup of data 

<img src="backup.png">

## step 2 : unmount lvm 

<img src="unmount.png">

## step 3 : lvremove

<img src="lvremove.png">

## step 4: remove vg 

<img src="vgremove.png">

## step 5 : remove pv

<img src="pvremove.png">






