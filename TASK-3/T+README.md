# Task 3 – Container Monitoring Automation

## Objective

Monitor Docker container CPU and memory usage automatically.

## Monitoring Script

monitor.sh

Script records:

* CPU Usage
* Memory Usage
* Timestamp

## Cron Job

crontab -e

Schedule

* * * * * /home/azureuser/monitor.sh

## Log File

/opt/container-monitor/logs/monitor.log

## Verification

cat monitor.log

## Result

Monitoring automated successfully.
