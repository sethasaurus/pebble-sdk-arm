# pebble-sdk-arm
Script to install Pebble SDK on Linux on Android

Tested on LinuxDeploy and UserSpace.
Make sure you have enough space on your LInux Deploy image!

Easiest method:
- Install debian distro on Linux Deploy or UserSpace:

  https://play.google.com/store/apps/details?id=ru.meefik.linuxdeploy&gl=us

- Install Pebble SDK

- Run this script (make sure to alter the path to your Pebble SDK

  (e.g. /home/username/pebble-dev/pebble-sdk-4.5-linux64 )
  
NOTE: qemu-pebble does not work so you need to install to phone in order to test:

pebble install --logs --phone=IPADDRESS
