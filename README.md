# ESP32-development-on-Ubuntu-VM-using-VirtualBox

Enable VT-x in BIOS

Install Silabs driver

Install VirtualBox

Download ubuntu desktop iso

Create new VM (must >4GB RAM, 80GB disk) and start it

Install ubuntu (basic installation) and make sure connect to ethernet

sudo apt update 

sudo apt upgrade -y

Mount Guest Addition ISO to VM as a cd-rom

Run the script: sudo ./VBoxLinuxAdditions.run

sudo apt install minicom

Check dialout group: getent group dialout

groups username

sudo adduser username dialout

Power off

Start again

lsusb or ls /dev/tty*


Plug in ESP32


Device -> USB -> Select the Silabs


lsusb or ls /dev/tty*    ->  ttyUSB0 appears


minicom -8 -b 115200 -D /dev/ttyUSB0

sudo apt install arduino

arduino (do not sudo arduino)

Install ESP32 boards







