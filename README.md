# rpihomeautomation

This is the project for managing my RPI 5. This will host:
- Joplin server
- Home assistant

## Setup of the RPI-5

### On fedora
Install rpi-manager `sudo yum install rpi-imager`
Install de docker_compose ansible module `ansible-galaxy collection install community.docker`

### On the RPI

Connect the USB-drive to the computer and with rpi-imager select the raspberry PI OS Lite (64-BIT) to install. After the procedure has been completed, connect the drive to the RPI 5 and it boots automatically from the drive. 

### Apply the Ansible playbook

Run `ansible-playbook site.yml`

## General project information
The [inventory](inventory) should contain only to the RPI hosts nebula IP-address.
