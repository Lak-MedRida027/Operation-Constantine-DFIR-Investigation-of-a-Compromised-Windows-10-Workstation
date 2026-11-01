---
tags: [analysis, quality]
---

# Limitations & Contamination

- **EID 10 caveat:** surviving LSASS ProcessAccess is benign Splunk service @ 2026-07-25 (acquisition boot), NOT attack-era. Real cred access = [[Invoke-Mimikatz cradle]]. Attack-era EID 10 destroyed by log clearing ([[T1070.001]]).
- **$J filter:** broad name match caught legit Splunk logs; splunkd.exe deletion is *inferred*.
- **Prefetch:** acquisition-boot entries excluded from [[Timeline (UTC)]].
- **PCAP time:** verified UTC (Z suffix + HTTP Date) — no offset needed.
