# Linux soft raid monitoring
New modern Template for Zabbix v7(6)


This template gives minimum monitoring of Linux mdadm/soft raids on Zabbix using simple common discovery without any additional steps. 
Just "Out of the Box".

- Download the template
- Add it to Zabbix server
- Add it to host.


**What this template does:**

- --> Discovers md-raids using discovery rule;
- --> Adds 4 data items for each raid discovered:
  + Raid Type,
  + Raid State,
  + Raid members,
  + Raid Sync State;
- --> Adds 2 Trigger Alerts for each raid discovered:
  + "Raid is degraded",
  + "Raid is sync state"


  p.s.
  
  have not tested it on Zabbix v6 yet!

 
---
#Use Perl or Die!
