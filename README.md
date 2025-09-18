# Linux soft raid monitoring
New modern Template for Zabbix v7(6)


This template gives a minimum of Linux mdadm/soft raids monitoring on Zabbix using simple common discovery without any additional steps. 
Just "out of the box".

## Steps

- Download the template
- Import it to Zabbix server
- Add it to a host.


## What this template does:

- Discovers md-raids using discovery rule;
- Adds 4 data items for the each raid:
  + Raid Type,
  + Raid State,
  + Raid members,
  + Raid Sync State;
- Adds 2 Trigger Alerts for the each raid:
  + "Raid is degraded",
  + "Raid is in a sync state"

 
---

  p.s.
  
  have not tested it on Zabbix 6 yet
