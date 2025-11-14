# ESP32-development-on-Ubuntu-VM-using-VirtualBox

Enable VT-x in BIOS

Install Silabs driver

Plug in ESP32 board and make sure it can be accessed by teraterm

Install VirtualBox

Download ubuntu desktop iso

Create new VM (must >4GB RAM, 80GB disk, skip unattended install) and start it

Install ubuntu (basic installation because smaller)

sudo apt update 

sudo apt upgrade -y

sudo apt install bzip2

Mount Guest Addition ISO to VM as a cd-rom

Run the script: sudo /media/wl/VBox_GAs_7.2.4/VBoxLinuxAdditions.run

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







