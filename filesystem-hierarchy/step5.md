Now that you've actually partitioned a disk, let's create a filesystem!

```
$ sudo mkfs -t ext4 /dev/vdb1
```

Simple as that! The `mkfs` (make filesystem) tool allows us to specify the type of filesystem we want and where we want it. You'll only want to create a filesystem on a newly partitioned disk or if you are repartitioning an old one. You'll most likely leave your filesystem in a corrupted state if you try to create one on top of an existing one. 

## Exercise

Make an `ext4` filesystem on the USB drive.

>>Q1: What command is used to create a filesystem?<<
=== mkfs
