# Attack Lifecycle & Frameworks

## 1. The Cyber Kill Chain (Lockheed Martin)
Focuses on the network-based attack flow:
1. **Reconnaissance**
2. **Weaponization**
3. **Delivery**
4. **Exploitation**
5. **Installation**
6. **Command & Control (C2)**
7. **Actions on Objectives**

## 2. The Unified Kill Chain
A modernized framework that bridges the gap between the Cyber Kill Chain and MITRE ATT&CK. It includes:
- **Infiltration**
- **Propagation**
- **Exfiltration**

## 3. MITRE ATT&CK Matrix
The industry standard for categorizing adversary behavior.

### Tactics (The "Why")
- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Defense Evasion
- Credential Access
- Discovery
- Lateral Movement
- Collection
- Exfiltration
- Command and Control
- Impact

### Techniques (The "How")
*Example:* T1566.001 (Phishing: Spearphishing Attachment)

---

## Operational Mapping Example
| Activity | Kill Chain Stage | ATT&CK Tactic |
| :--- | :--- | :--- |
| Sending a malicious email | Delivery | Initial Access |
| Modifying registry keys | Installation | Persistence |
| Scanning local network | Actions on Obj | Discovery |

---

### **[MITRE ATT&CK Navigator]**
* **Category:** Fundamentals
* **Type:** Tool
* **Summary:** Interactive tool to visualize and map detections to the ATT&CK matrix.
* **Link:** https://mitre-attack.github.io/attack-navigator/
