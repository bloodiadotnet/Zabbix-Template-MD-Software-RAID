# Zabbix Template MD Software RAID
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/bloodiadotnet/Zabbix-Template-MD-Software-RAID/blob/master/LICENSE)

## Overview
Monitoring software RAID devices status with Zabbix template.  

## Requires
### OS
- CentOS 5.x - 7.x

### Software RAID
- Linux Software RAID (Multiple Devices)

### Zabbix
- 3.4
- 4.0

## How to Install
### UserParameter Config
- Copy "UserParameter Config" file (conf) to /etc/zabbix/zabbix_agentd.d and restart Zabbix agent.  

### Template
- Import the template file (xml) and assign it to the host monitored.

## Author
[@bloodiadotnet](https://twitter.com/bloodiadotnet)
