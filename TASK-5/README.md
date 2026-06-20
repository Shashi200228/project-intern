# Task 5 – Firewall Configuration

## Objective

Allow only required traffic and restrict unauthorized access.

## Installed UFW

sudo apt install ufw -y

## Firewall Rules

Allow SSH

sudo ufw allow from YOUR_IP to any port 22

Allow HTTP

sudo ufw allow 80

Allow Port 8000

sudo ufw allow 8000

Enable Firewall

sudo ufw enable

## Verification

sudo ufw status

## Result

Firewall successfully configured.
