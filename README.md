 Title: Multi-purpose Automation Scripts and Configurations for Various Devices

This repository contains a collection of Ansible playbooks and scripts for automating various tasks on different devices. The following devices are supported:

1. Trade Server (Raspberry Pi): Contains scripts and configurations for enabling the camera, managing battery levels, and creating a road cam for traffic monitoring.

2. Rank App Server (Generic Linux): Includes scripts and configurations for setting up a virtual web host, managing databases, and scheduling review checks using Selenium.

Please find below detailed explanations of each directory:

**batterylow:** Contains the Ansible playbook to convert Python scripts into road cams on Raspberry Pi devices. This script also disables unnecessary services, updates the firmware, and installs required packages.

**camrecorder.service:** Service file for managing the video recording process on a Raspberry Pi camera.

**cleardb.py:** Python script to clear a SQLite database by removing the existing file.

**makepyroadcam.yml:** Ansible playbook for configuring and setting up the road cam application on Raspberry Pi devices.

**readme.md:** Detailed instructions on how to utilize the pi-cam scripts and configurations for traffic monitoring using a Raspberry Pi camera.

**batterylow.service:** Service file for shutting down the system when battery levels are critically low on Raspberry Pi devices.

**rankapp:** Contains various playbooks, services, and scripts for managing the Rank App server, including setting up virtual web hosts, scheduling review checks using Selenium, clearing databases, and removing the app server completely.

**raspicam:** Directory containing Ansible playbooks and scripts specific to Raspberry Pi devices, such as enabling the camera, managing battery levels, and creating a road cam for traffic monitoring.

**realwebhost.ini:** Ini configuration file for setting up virtual web hosts on various devices.

**raspberrypi-batterylow.service:** Service file for shutting down Raspberry Pi devices when battery levels are critically low.

**rankappremove.yml:** Ansible playbook for completely removing the Rank App server from a system.

**virtualwebhost.ini:** Ini configuration file for setting up virtual web hosts on various devices.

**seleniumsearchfind:** A script that schedules review checks using Selenium on the Rank App server.

**raspicam-makepyroadcam.yml:** Ansible playbook for configuring and setting up the road cam application on Raspberry Pi devices.

**bottlyapp:** Contains scripts and configurations for setting up a virtual web host, managing databases, and scheduling review checks using Selenium on the Trade Server.

**bottly_server.ini:** Ini configuration file for setting up the WSGI server on the Trade Server.

**camrecorder.service:** Service file for managing the video recording process on the Trade Server.

**cleardb.py:** Python script to clear a SQLite database by removing the existing file on the Trade Server.

**readme.md:** Detailed instructions on how to utilize the scripts and configurations provided in this repository, including setting up the Trade Server and managing databases.