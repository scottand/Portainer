# HomeAssistant
Used for HomeAssistant instance on Raspberry Pi 4

Docker compose INSTALL file based on:
https://www.home-assistant.io/installation/raspberrypi/#docker-compose

- Set to always restart if container goes down
- Allowing Conbee2 USB device to pass through from host to container
- Ensuring config file is correctly referenced from outside of the container so image updates will not affect user settings/scripts etc.
