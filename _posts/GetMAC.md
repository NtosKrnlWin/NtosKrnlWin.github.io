---
title: "Get MAC address from command line (CMD)"
date: 2017-11-19 09:49:00
tags: Network Markdown
---

```bat
netsh interface ipv4 show interfaces
getmac
wmic nic get macaddress
wmic nic where netconnectionid!=NULL get macaddress
powershell Get-WmiObject win32_networkadapter
```