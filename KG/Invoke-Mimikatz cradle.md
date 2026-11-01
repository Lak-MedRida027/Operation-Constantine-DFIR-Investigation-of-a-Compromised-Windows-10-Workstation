---
tags: [artifact, ioc, cred-access]
---

# Invoke-Mimikatz cradle

- PowerShell `-ExecutionPolicy Bypass` + `DownloadString(...)` from `raw.githubusercontent.com`, `-DumpCreds`
- UtcTime 2026-07-05 07:27:10.361 (host) — [[Sysmon]] EID 1
- Corroborated on wire: TLS SNI `raw.githubusercontent.com` @ 07:27:10.651 UTC ([[PCAP]])
- SHA256 (powershell.exe): `9785001B0DCF755EDDB8AF294A373C0B87B2498660F724E76C4D53F9C217C7A3`

Techniques: [[T1059.001]] · [[T1003.001]] · [[T1105]]
