# Official documentation
* [https://www.zabbix.com/documentation/guidelines/en/thosts/configuration/template_items#tags Items tags]

# Items tags


| Tag | Value | Description| Examples |
| --- | ---| --- | --- |
| component| application | |
|| business ||
|| cpu | | 
|| device | |
|| environment ||
|| kpi ||
|| memory || 
|| network ||
|| os ||
|| raw | raw data, master item | vfs.fs.get |
|| sensor || Temperature, voltage|
|| storage || 
|| system |Metrics not related to os| ping, uptime, hostname
| disk | {#DEVNAME}| | maybe just about actual disks? |
| filesystem | {#FSNAME} ||
| fstype | {#FSTYPE} ||


