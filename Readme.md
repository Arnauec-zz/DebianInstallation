#Packages to install when installing debian
su
apt-get install sudo
sudo adduser <username> sudo

#Restart the machine
sudo apt-get install build-essentials synaptic linux-headers*

#If you can't install VBoxGuestAdditions
--> Go to /etc/fstab
--> Add exec after noauto
