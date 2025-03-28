# FortiSupport Firewall Commands
useful FortiSupport diagnostic commands for monitoring and troubleshooting FortiGate firewalls. These commands can help you check system performance, routing, logs, firewall settings, VPN statuses, and much more.

## System Status & Performance
### Get system status
```shell
get system status
```
### Get system performance status
```shell
get system performance status
```
### Get router info routing-table details
```shell
get router info routing-table details 0.0.0.0
```
### Get system auto-update versions
```shell
get system auto-update versions
```
### Read crash logs
```shell
diagnose debug crashlog read
```
### Reset debug logs
```shell
diagnose debug reset
```
### Enable debugging
```shell
diagnose debug enable
```
## Firewall Commands

### Firewall IP List
```shell
diagnose firewall iplist list
```
### Firewall IP-MAC List
```shell
diagnose firewall ipmac list
```
### Firewall IP-MAC Status
```shell
diagnose firewall ipmac status
```
### Firewall Policy Route
```shell
get firewall proute
```
### Firewall Schedule List
```shell
diagnose firewall schedule list
```
### Get Firewall Performance Statistics
```shell
get system performance firewall statistics
```
## Routing & VPN

### Get full router info
```shell
get router info routing-table all
```
### Get router info routing-table database
```shell
get router info routing-table database
```
### Get VPN IPSEC stats (crypto)
```shell
get vpn ipsec stats crypto
```
### Get VPN IPSEC tunnel details
```shell
get vpn ipsec tunnel details
```
### Get VPN Status SSL List
```shell
get vpn status ssl list
```
## Web Filtering & Email Filtering

### Web filter statistics
```shell
get webfilter ftgd-statistics
```
### Web filter status
```shell
get webfilter status
```
### Email filter FortiShield statistics list
```shell
diagnose emailfilter fortishield statistics list
```
### Email filter FortiShield servers
```shell
diagnose emailfilter fortishield servers
```
## System Information & Debugging

### Get system session info statistics
```shell
get sys session-info statistics
```
### Get system session info TTL
```shell
get system session-info ttl
```
### Get system session helper info list
```shell
get system session-helper-info list
```
### System flash memory list
```shell
diagnose sys flash list
```
### System disk usage info
```shell
fnsysctl df –k
```
### System log disk status
```shell
diagnose sys logdisk status
```
### System status for HA (High Availability)
```shell
show full-configuration system ha
```
### Get HA status
```shell
diagnose sys ha status
```
### Show HA checksum
```shell
diagnose sys ha checksum show
```
## Hardware & NIC Information

### Get hardware NIC mgmt2 info
```shell
get hardware nic mgmt2
```
### Get hardware NIC port40 info
```shell
get hardware nic port40
```
### Get hardware NIC port39 info
```shell
get hardware nic port39
```
### Get hardware NIC port37 info
```shell
get hardware nic port37
```
### Get hardware NIC port36 info
```shell
get hardware nic port36
```
### Get hardware NIC port35 info
```shell
get hardware nic port35
```
## Proxy & SIP Proxy

### Proxy memory usage
```shell
diag sys proxy memory usage
```
### Proxy stats all
```shell
diag sys proxy stats all
```
### Proxy SSL exempt list
```shell
diag sys proxy ssl exempt list
```
### SIP Proxy session list
```shell
diagnose sys sip-proxy session list
```
### SIP Proxy config list
```shell
diagnose sys sip-proxy config list
```
### SIP Proxy stats proto
```shell
diagnose sys sip-proxy stats proto
```
### SIP Proxy stats call
```shell
diagnose sys sip-proxy stats call
```
### SIP Proxy UDP stats
```shell
diagnose sys sip-proxy stats udp
```
### SIP Proxy calls idle
```shell
diagnose sys sip-proxy calls idle
```
### SCCP Proxy stats list
```shell
diagnose sys sccp-proxy stats list
```
## Test Commands

### Test IMAP
```shell
get test imap 444
```
### Test NNTP
```shell
get test nntp 444
```
### Test POP3
```shell
get test pop3 444
```
### Test SMTP
```shell
get test smtp 444
```
### Test FTPD
```shell
get test ftpd 444
```
### Test URL Filter
```shell
get test urlfilter 10
```
### Test IPS monitor 1
```shell
get test ipsmonitor 1
```
### Test IPS monitor 3
```shell
get test ipsmonitor 3
```
### Test Radiusd 5
```shell
get test radiusd 5
```
### Test Application miglogd
```shell
diagnose test application miglogd 6
```
### Test Application quarantined
```shell
diagnose test application quarantined 2
```
## Scan Unit and Debugging

### Clear scan unit filter
```shell
diag sys scanunit filter clear
```
### Scan unit stats all
```shell
diagnose sys scanunit stats all
```
## WAD (Web Application Debugging)

### WAD memory sum
```shell
diagnose wad memory sum
```
### WAD stats common
```shell
diagnose wad stats common
```
### WAD stats worker
```shell
diagnose wad stats worker
```
### WAD stats algorithm
```shell
diagnose wad stats algo
```
### WAD stats dispatcher
```shell
diagnose wad stats dispatcher
```
### WAD webcache stats
```shell
diagnose wad worker webcache stats
```
### WAD bytecache stats
```shell
diagnose wad worker bytecache stats
```
### WAD memcache stats
```shell
diagnose wad worker memcache stats
```
## System Information & Process Monitoring

### System top command for processes
```shell
diagnose sys top-all 1 100 1
```
### Check sock-mem for IPS engine
```shell
diagnose sys process sock-mem ipsengine
```
### Check sock-mem for WAD
```shell
diagnose sys process sock-mem wad
```
### Check sock-mem for ProxyD
```shell
diagnose sys process sock-mem proxyd
```
### Generate system profile report
```shell
diagnose sys profile report
```
