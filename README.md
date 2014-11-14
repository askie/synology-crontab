synology-crontab
================

enable synology crontab on DSM 5.0

download the crontab file into /sbin/
and update the permissions (chmod 755 /sbin/crontab). 

From now on, you will be able to run the usual crontab commands:

crontab -l: list the crontab content
crontab -e: edit the crontab content and restart cron daemon if content is valid
crontab -f: restart cron daemon
crontab -h: show help


Big thanks to John Kelly for putting this together. This is a great help!


