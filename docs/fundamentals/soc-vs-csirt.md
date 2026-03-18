# SOC vs CSIRT vs CERT

## Definitions

| Term | Full Name | Primary Focus | Scope |
| :--- | :--- | :--- | :--- |
| **SOC** | Security Operations Center | Monitoring & Detection | Operational (Day-to-day) |
| **CSIRT** | Computer Security Incident Response Team | Response & Mitigation | Event-driven (Tactical) |
| **CERT** | Computer Emergency Response Team | Coordination & Research | Strategic / Support |

## Key Differences

### 1. Operation Style
- **SOC:** Built for 24/7/365 monitoring. They catch the "smoke" in the logs.
- **CSIRT:** May not be 24/7. They are the "firefighters" called in when a SOC confirms an incident.

### 2. Objectives
- **SOC Objective:** Minimize the **Time to Detect (MTTD)**.
- **CSIRT Objective:** Minimize the **Time to Respond (MTTR)** and recover.

### 3. Resource Types
- **SOC Team:** Analysts (L1, L2), Detection Engineers, Tool Admins.
- **CSIRT Team:** Forensic experts, Incident responders, PR/Legal liaisons, Malware reverse engineers.

## Modern Convergence
In modern organizations, the boundaries are blurring. Many **Next-Gen SOCs** include CSIRT functions within their L2 and L3 tiers to ensure a seamless flow from detection to eradication.

---

### **[Maturity Comparison: SOC-CMM]**
* **Category:** Fundamentals
* **Type:** Whitepaper
* **Summary:** Compares different organizational models for security operations.
* **Link:** https://www.soc-cmm.com/
