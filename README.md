# Mount and edit ubifs files.

# Ubuntu 20.04

Install mtd utils for ubi commands

`sudo apt install mtd-utils`

Test ubi commands by using `ubinfo` command. 
If there is an error like `ubinfo: error!: UBI is not present in the system` use `sudo modprobe ubifs` command for load kernel modules for Ubuntu.
