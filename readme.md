This version is for Raspberry Pi3

enter SSH in your Pistar

Put the system in RW with

rpi-rw

Clone the GIT:

git clone https://github.com/EA5SW/Pi-star-mods-pi3

Enter folder cd Pi-start-mods-nano

stop the MMDVM

sudo systemctl stop mmdvmhost.service

change to exe the files

chmod 755 .

execute the install script

./install.sh
