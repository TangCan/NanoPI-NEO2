apt-get update
apt-get upgrade
# change password for root user
passwd
# add a new user with sudo group
useradd -m -s /bin/bash richard
adduser richard sudo
passwd richard

shutdown -P now

# Need unplug the USB Type C cable and plug again to power on the chip

sudo apt install openjdk-8-jdk
sudo apt install screen
sdk install gradle
sdk install kotlin
