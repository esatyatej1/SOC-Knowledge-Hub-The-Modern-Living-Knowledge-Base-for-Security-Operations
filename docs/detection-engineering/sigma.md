# Sigma Rules for SOC

## What is Sigma?
Sigma is a generic and open signature format that allows you to describe relevant log events in a straightforward manner. Think of it as "YARA for Logs."

## Rule Structure
```yaml
title: Suspicious PowerShell Download
status: experimental
description: Detects powershell.exe downloading content from external sites
logsource:
    product: windows
    service: powershell
detection:
    selection:
        EventID: 4104
        ScriptBlockText|contains:
            - 'Net.WebClient'
            - 'DownloadFile'
            - 'Invoke-WebRequest'
    condition: selection
falsepositives:
    - Administrative scripts
level: medium
```

## Why SOC Teams Use Sigma
1. **Tool Independence:** Write once, convert to Splunk, Sentinel, or Elastic.
2. **Community Sharing:** Massive repository of community rules.
3. **Collaboration:** Security researchers can share detections without needing the same tech stack.

---

### **[SigmaHQ Official Repository]**
* **Category:** Detection Engineering
* **Type:** Resource
* **Summary:** The main repository containing thousands of Sigma rules.
* **Link:** https://github.com/SigmaHQ/sigma

### **[Uncoder.io]**
* **Category:** Detection Engineering
* **Type:** Tool
* **Summary:** Online converter for Sigma rules into SIEM queries.
* **Link:** https://uncoder.io/
