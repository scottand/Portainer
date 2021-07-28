# HomeAssistant
Used for HomeAssistant instance on Raspberry Pi 4

Docker compose INSTALL file based on:
https://www.home-assistant.io/installation/raspberrypi/#docker-compose

- Set to always restart if container goes down
- Allowing Conbee2 USB device to pass through from host to container
- Ensuring config file is correctly referenced from outside of the container so image updates will not affect user settings/scripts etc.

# Update Home Assitant image:
1. Open Portainer
2. Go to 'Stacks'
3. Open 'homeassistantgitversioned'
4. Click 'Editor'
5. Click 'Update the stack'
6. Wait for a few minutes whilst the update happens.
7. Once update complete delete the old image from the 'Images' section in Portainer
