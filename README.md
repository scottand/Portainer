# HomeAssistant
Used for HomeAssistant instance on Raspberry Pi 4

Docker compose file copied from:
https://www.home-assistant.io/installation/raspberrypi/#platform-installation

- Set to always restart if container goes down
- Allowing Conbee2 USB device to pass through from host to container
- Ensuring config file is correctly referenced from outside of the container so image updates will not affect user settings/scripts etc.
