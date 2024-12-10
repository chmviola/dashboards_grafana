# Dashboard Repository for Grafana

How to use:

The dashboards were created using Zabbix as a data source.  
The only plugin used that does not come standard in Grafana is the Clock Panel \- [https://grafana.com/grafana/plugins/grafana-clock-panel/](https://grafana.com/grafana/plugins/grafana-clock-panel/)

## Dashboards:

1. **Linux Server Status Dashboard**

Dashboard for managing basic Linux server information.

### Prerequisites

* Data source: Zabbix  
* Required plugin: \[Clock Panel\](https://grafana.com/grafana/plugins/grafana-clock-panel/)  
* Configure the \`Group\` and \`Server\` variables on the Dashboard with the Linux server host group.

### Available panels

* Time and hostname  
* Operating system  
* CPU: CPU time graph and CPU load graph  
* Memory: Available in GB and in use (%)  
* Zabbix agent version  
* Graphs: Ping, processes, logged in users and network traffic  
* Disk: Available space, usage and read and write I/O  
* Issues dashboard

2. **Windows Status Dashboard**

### Prerequisites

* Data source: Zabbix  
* Required plugin: \[Clock Panel\](https://grafana.com/grafana/plugins/grafana-clock-panel/)  
* Configure the \`Group\` and \`Server\` variables on the Dashboard with the Linux server host group.

### Available panels

* Time and hostname  
* Operating system  
* CPU: CPU time graph and CPU load graph  
* Memory: Available in GB and in use (%)  
* Zabbix agent version  
* Graphs: Ping, processes, logged in users and network traffic  
* Disk: Available space, usage and read and write I/O  
* Issues dashboard

