# Task 1 – SSH Server Setup

## Objective

Configure secure SSH remote access using SSH key-based authentication.

## Steps Implemented

Installed SSH server

sudo apt install openssh-server -y

Generated SSH key

ssh-keygen

Copied public key

ssh-copy-id azureuser@SERVER_IP

Disabled password login

sudo nano /etc/ssh/sshd_config

Configuration changed

PasswordAuthentication no

Restarted SSH

sudo systemctl restart ssh

## Verification

Connected successfully without password.

ssh azureuser@SERVER_IP

## Result

Passwordless authentication successfully configured.
