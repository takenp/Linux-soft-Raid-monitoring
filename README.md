# Linux-soft-Raid-monitoring
New modern Template for Zabbix


This template start minimum monitoring of mdadm soft raids on Linux using simple common Zabbix-discovery without any additional steps. "Out of the Box".

[1] Download the template
[2] Add it to Zabbix server
[3] Add it to host.

What this template does:

--> Discovers md-raids using discovery rule;
--> Adds 4 data items for each raid discovered: Raid Type, Raid State, Raid members, Raid Sync State;
--> Adds 2 Trigger Alerts for each raid discovered: "Raid is degraded" and "Raid is sync state".
