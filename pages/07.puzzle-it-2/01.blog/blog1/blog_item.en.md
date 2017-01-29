---
title: 'Zabbix server, agent and proxy spk'
published: true
date: '03-03-2015 19:12'
---

Compiled the latest Zabbix (2.4.4) for my Synology DS214Play (evansport) using the repository of RustyPixel which is not online anymore :-(. Updated the various subpackages to the latest version possible, except mysql which is still on 5.6.22 since 5.6.23 has a compile time error which I haven't been able to track down yet. See below for links to the source repo and binary spk. 
  * Source to recompile yourself:<br>
```git clone https://voorhuis.xs4all.nl:8443/r/spksrc.git```
  * SPK package for DS214Play:<br>
```https://voorhuis.xs4all.nl:8443/raw/zabbix-spk.git/master/zabbix_evansport_2.4.4-1.spk```
