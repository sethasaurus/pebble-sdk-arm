# pebble-sdk-arm
Script to install Pebble SDK on Linux on Android / ARM

Tested on LinuxDeploy and UserLand.

Easiest method:
- Install debian distro on Linux Deploy or UserLand:

  https://play.google.com/store/apps/details?id=ru.meefik.linuxdeploy&gl=us

  https://play.google.com/store/apps/details?id=tech.ula&gl=US&pli=1

- Install Pebble SDK

- Run this script (make sure to alter the path to your Pebble SDK

  (e.g. /home/username/pebble-dev/pebble-sdk-4.5-linux64 )
  
NOTE: If installing in Userland or LinuxDeploy, qemu-pebble will not work.

 - you need to install watchfaces/apps via developer mode on Pebble app in order to test:

pebble install --logs --phone=IPADDRESS
