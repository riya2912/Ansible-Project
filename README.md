# Automated Security Patching

## Overview

This project focuses on implementing automated security patching for Linux servers using Ansible, dynamic inventory from AWS, and Ansible Vault for securely storing sensitive data. The project aims to enhance security and system stability by keeping servers up-to-date with the latest security patches.

## Features

- Automate the process of checking for and applying security patches.
- Utilize Ansible playbooks and roles for modularity and ease of management.
- Use AWS dynamic inventory to dynamically fetch information about Linux servers(ansible managed nodes).

## Prerequisites

Before getting started with this project, make sure you have the following:

- Ansible installed on your control node.
- An AWS account with Linux servers provisioned.
- Sensitive data like SSH keys securely stored in an Ansible Vault file.

## Usage

1. Clone this repository to your Ansible control node.

2. Set up your AWS dynamic inventory script and configuration to fetch information about your fleet of Linux servers. Ensure that AWS CLI credentials are properly configured.

3. Create or update your Ansible Vault file to securely store sensitive data. You can create a new vault file using the `ansible-vault create` command.

4. Customize the Ansible playbook and roles as needed for your specific requirements.

5. Run the playbook using the `ansible-playbook` command.
