## Baseline Summary

### System:
- Windows 10 Enterprise VM (Practice-Labs environment)

### Baseline Commands Run:
- `systeminfo > baseline_systeminfo.txt`
- `tasklist > baseline_tasks.txt`
- `Get-FileHash` used on critical files in `C:\Windows\System32`
- Registry keys reviewed: `HKLM\Software\Microsoft\Windows\CurrentVersion\Run`

### Change Detection Strategy:
- Noted SHA256 hashes of config files
- Exported key system logs before/after modifications
- Event logs reviewed for ID 4688 and 7045

### Findings:
- Baseline successfully captured and stored
- Post-change comparison showed service injection from test tool
- Log integrity verified and restored

---

