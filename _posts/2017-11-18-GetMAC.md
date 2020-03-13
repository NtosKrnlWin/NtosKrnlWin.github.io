---
title: "Get MAC address from command line (CMD)"
tags: Network,MAC
---

```bat
netsh interface ipv4 show interfaces
getmac
wmic nic get macaddress
wmic nic where netconnectionid!=NULL get macaddress
powershell Get-WmiObject win32_networkadapter
```
