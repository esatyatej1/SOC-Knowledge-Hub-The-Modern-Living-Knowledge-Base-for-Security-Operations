# Detection Engineering Lifecycle

## What is Detection Engineering?
Detection Engineering is the practice of building, maintaining, and improving the logic used to identify cyber threats. It is a continuous cycle of research, implementation, and feedback.

## The Lifecycle Stages
1. **Threat Research:** Understanding adversary techniques (e.g., using MITRE ATT&CK).
2. **Hypothesis Generation:** Defining what "malicious" looks like for a specific technique.
3. **Data Availability Check:** Ensuring the necessary telemetry (logs) exists to detect the threat.
4. **Rule Development:** Writing the detection logic (Sigma, KQL, SPL, YARA).
5. **Testing & Validation:** Using breach and attack simulation (BAS) to verify the rule.
6. **Deployment:** Pushing the rule to production.
7. **Maintenance & Tuning:** Reducing false positives and updating rules as threats evolve.

## Detection Formats
- **[Sigma](https://github.com/SigmaHQ/sigma):** Generic signature format for SIEM rules.
- **[YARA](http://virustotal.github.io/yara/):** Tool for malware identification and classification.
- **KQL (Kusto Query Language):** Primarily used in Microsoft Sentinel and Defender.
- **SPL (Search Processing Language):** Used in Splunk.

---

### **[The Detection Engineering Handbook]**
* **Category:** Detection Engineering
* **Type:** Book / Guide
* **Summary:** Highly detailed guide on implementing detection engineering as a discipline.
* **Why it matters:** It is the "Bible" for modern detection engineers.
* **Best for:** Detection Engineers, L3 Analysts
* **Difficulty:** Advanced
* **Scope:** Vendor-neutral
* **Trust Level:** High
* **Last Validated:** 2026-03
* **Link:** https://github.com/Detection-Engineering-Handbook/handbook
