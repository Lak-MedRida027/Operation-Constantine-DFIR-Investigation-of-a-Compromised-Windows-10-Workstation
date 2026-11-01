---
tags: [evidence, network]
---

# PCAP (Wireshark)

- `POST /beacon` to [[C2 Server (192.168.67.128)]]; Go-http-client UA; aiohttp banner
- Agent profile (Base64) cross-links to [[anmar_hacking.exe]] (paw `qktity`, pid 5636)
- Conversations: beacon stream 0 (62883->8888), ~508 kB, ~5390 s
- Exfil `POST /file/upload` x2 (07:21:59, 08:28:32 UTC) — [[T1041]]
- TLS SNI `raw.githubusercontent.com` corroborates [[Invoke-Mimikatz cradle]]
- All timestamps verified UTC (Z suffix / HTTP Date) — see [[Limitations & Contamination]]

Techniques: [[T1071.001]] · [[T1105]] · [[T1041]]
