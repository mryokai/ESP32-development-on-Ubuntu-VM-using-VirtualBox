# ESP32-development-on-Ubuntu-VM-using-VirtualBox

Enable VT-x in BIOS

Install VirtualBox

Download ubuntu desktop iso

Create new VM and start it

Make sure connect to wifi

sudo update && sudo upgrade -y


Mount Guest Addition ISO to VM as a cd-rom

Run the script: sudo ./VBoxLinuxAdditions.run


Check dialout group: getent group groupname

groups username

sudo adduser username dialout

logout and login


Plug in ESP32

lsusb

ls /dev/tty*

sudo minicom -8 -b 115200 -D /dev/ttyUSB0

sudo apt install arduino





