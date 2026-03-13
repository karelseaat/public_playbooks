# Multi-Platform Web Hosting Automation Scripts

This repo holds Ansible playbooks for setting up virtual web hosting on different systems—particularly Raspberry Pi and Ubuntu servers. Each playbook is tied to a specific project, but they follow a shared structure to keep things maintainable.

## Projects

### `apprank`
Deploys a web app for monitoring and analyzing mobile app data.  
Includes playbooks for:

- Setting up the virtual host  
- Database configuration  
- Backup/restore automation  
- Enabling/disabling services  

**Main playbook:** `apprank.yml`  

### `pi-cam`
Turns a Raspberry Pi into a road camera using existing Python scripts.  
Includes playbooks for:

- System updates and dependency installation  
- Cloning the project repo  
- Camera configuration  
- Low-battery shutdown handling  

**Main playbook:** `makepyroadcam.yml`  

## How to use

1. Install Ansible on your machine.  
2. Open the project’s folder (e.g., `apprank/` or `pi-cam/`) and follow its `README.md`.  

These playbooks are opinionated and assume certain defaults. Review and adjust configuration files (variables, paths, user settings, etc.) before running—especially if your environment differs.

## Notes

- Some playbooks may need tweaks depending on your exact setup or OS version.  
- Always test on a non-production system first.  

—  
Use these as a starting point to streamline your own deployments.