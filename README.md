# Vagrant + Ansible Project

## Overview

This repository contains a Vagrant and Ansible project for deploying multiple applications on virtual machines. The project includes setup and provisioning for three different applications:

1. **Appflowy**: A sample application.
2. **RocketChat.ReactNative**: The React Native client for Rocket.Chat.
3. **RocketChat**: The Rocket.Chat server.

The project structure is organized as follows:

- `vagrant/`: Contains the Vagrant configuration files.
- `ansible/`: Contains Ansible playbooks, inventory, and configuration.
- `README.md`: You are reading this file.

## Getting Started

To set up and run the project, follow these steps:

1. Make sure you have Vagrant and Ansible installed on your local machine.

2. Clone this repository:

   ```bash
   git clone <repository_url>

Create and configure the Vagrant virtual machines by running:
vagrant up

We manage Ansible roles and collections using the requirements.yml file. You can install them with the following command:
ansible-galaxy install -r ansible/requirements.yml
