# Task 4 – Secure Monitoring Logs

## Objective

Restrict monitoring logs access to authorized user.

## Steps Implemented

Created user

sudo useradd monitoruser

Changed ownership

sudo chown -R monitoruser /opt/container-monitor

Applied permissions

sudo chmod -R 700 /opt/container-monitor

## Verification

Unauthorized users denied access.

Permission denied

## Result

Monitoring logs secured successfully.
