# Incident Summary Template

Use this template to document the findings of a security investigation for management and technical review.

---

## **1. Executive Summary**
* **Incident ID:** [INC-XXXXX]
* **Priority:** [Critical / High / Medium / Low]
* **Detection Time:** [YYYY-MM-DD HH:MM UTC]
* **Containment Time:** [YYYY-MM-DD HH:MM UTC]
* **Status:** [Closed / Resolved]
* **Short Description:** [One sentence summary]

## **2. Incident Scope**
* **Affected Systems:** [Hostnames, IPs]
* **Affected Users:** [Usernames, Emails]
* **Data Impacted:** [e.g., PI, Sensitive Intellectual Property]
* **Vector:** [e.g., Phishing, SQL Injection]

## **3. Timeline of Events**
| Timestamp (UTC) | Action / Event Description | Source / Evidence |
|-----------------|----------------------------|-------------------|
| 09:00           | Initial alert triggered   | SIEM Rule X       |
| 09:15           | Host isolation initiated  | EDR Action        |
| 10:30           | Root cause identified     | Analysis          |

## **4. Root Cause Analysis (RCA)**
[Detailed explanation of how the attack occurred and what vulnerability was exploited.]

## **5. Remediation Actions**
- [ ] List action item 1
- [ ] List action item 2

## **6. Lessons Learned**
* **What went well:** [e.g., Fast containment]
* **What could be improved:** [e.g., Missing logs for X service]
* **Tuning Recommendations:** [e.g., Update rule Y to reduce noise]
