# Linux Chaos

Following are the commands which will help in performing some quick chaos in Linux. 

DO NOT RUN IN PROD or YOUR PERSONAL LAPTOP. RUN IT IN ISOLATED ENVIRONMENT WHICH YOU DO NOT CARE.

## Disk Fill

Below command fills the disk pretty quick.

```
cat /dev/zero > /var/log/diskchaos.log
```
