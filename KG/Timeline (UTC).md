---
tags: [analysis, timeline]
---

# Timeline (UTC)

| Time | Event | Technique | Source |
|------|-------|-----------|--------|
| 06:13:27 | splunkd.exe first exec | [[T1204.002]] | [[Amcache]] |
| 06:38:48 | anmar_hacking.exe first seen | [[T1204.002]] | [[Amcache]] |
| ~07:01 | Event logs cleared | [[T1070.001]] | EVTX gap |
| 07:16:43 | C2 beacon 200 OK | [[T1071.001]] | [[PCAP]] |
| 07:21:59 | Exfil cycle 1 | [[T1041]] | [[PCAP]] |
| 07:27:10 | Invoke-Mimikatz + GitHub SNI | [[T1003.001]] | [[Sysmon]]/[[PCAP]] |
| 08:20:22 | Hidden $ account | [[T1136.001]] | [[Sysmon]]/[[Registry (RECmd)]] |
| 08:27:44 | staged.zip re-stage | [[T1560.001]] | [[USN Journal]] |
| 08:28:32 | Exfil cycle 2 | [[T1041]] | [[PCAP]] |
