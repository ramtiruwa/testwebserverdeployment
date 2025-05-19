# Webserver Setup Ansible Playbook

This is an Ansible playbook to automate the installation and configuration of a webserver on Red Hat-based systems.

## Features
- Supports installing either Apache (`httpd`) or Nginx webserver.
- Ensures the webserver service is enabled and running on system boot.
- Customizes the default web page to display a message based on a user-provided variable.

## Files
- `webserver_setup.yml` - Main Ansible playbook.
- `inventory.example` - Example Ansible inventory file.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/webserver-setup-ansible.git
   cd webserver-setup-ansible
