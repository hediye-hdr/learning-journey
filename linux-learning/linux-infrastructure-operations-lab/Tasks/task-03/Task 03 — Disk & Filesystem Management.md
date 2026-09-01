
## Scenario

```
A new virtual disk was added to a Debian Linux server.

The objective was to prepare the disk for company data by creating
a partition, formatting it with ext4, mounting it to a dedicated
directory, and configuring persistent mounting after system reboot.

```
## Objectives
```

Identify the newly attached disk
Create a partition
Create an ext4 filesystem
Create a dedicated mount point
Mount the filesystem
Identify the filesystem UUID
Configure persistent mounting using `/etc/fstab`
Verify the configuration
Test the configuration after reboot

```
## Environment

```
 Operating System: Debian 13
 Virtualization: VirtualBox
 Filesystem: ext4
 Shell: Bash

```


