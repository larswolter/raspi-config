# raspi-config
Some scripts and settings to configure some raspberry pis

## Basic setup
Use `raspi-config` to set hostname, display options, localization for WLAN and enable SSH

Install docker
```sh
sudo curl -fsSL https://get.docker.com | sh
sudo apt install -y python3 python3-pip
sudo pip3 install docker-compose
```
# Setup external USB

configure usb device to automount. 
# list UUIDs
# create mount point
# Add `UUID=xxx /mnt/data ext4 defaults,noatime 0 0` to fstab

```sh
sudo ls -l /dev/disk/by-uuid/
sudo mkdir /mnt/data
sudo nano /etc/fstab
```
