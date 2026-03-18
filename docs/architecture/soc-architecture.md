# SOC Architecture

## Designing a Resilient SOC
Modern SOC architecture must be scalable, observable, and integrated. It focus on the flow of telemetry from data sources to the analyst's workstation.

## Core Components
1. **Data Sources:** Endpoints (EDR), Network (NDR), Cloud (CSPM), Identity (IDP), Email.
2. **Data Pipeline:** Filtering, normalization, and enrichment of logs before they reach the SIEM.
3. **SIEM / XDR:** The central brain where data is correlated and alerts are generated.
4. **SOAR:** Automation platform for orchestration and repeatable response workflows.
5. **Threat Intelligence Platform (TIP):** Aggregates and scores IoCs to inform detections.
6. **Case Management:** Tracks incident progress and maintains evidence.

## High-Level Architecture Patterns
- **Centralized SOC:** One single SOC for the entire organization.
- **Hub-and-Spoke:** A main global SOC with regional specialized units.
- **MSSP / MDR:** Outsource some or all operations to a third party.
- **Distributed / Remote SOC:** No physical office, fully cloud-based operations.

## The Detection Pipeline
A modern detection pipeline consists of:
`Logs -> Normalization -> Enrichment (e.g., GeoIP, Asset Info) -> Rule Matching -> Triage -> Response`

---

### **[Gartner SOC Architecture Guide]**
* **Category:** SOC Architecture
* **Type:** Research / Whitepaper
* **Summary:** Comprehensive guide on structuring a modern security operations center.
* **Why it matters:** Provides industry-standard blueprints for enterprise SOCs.
* **Best for:** SOC Architects, SOC Managers
* **Difficulty:** Advanced
* **Scope:** Vendor-neutral
* **Trust Level:** High
* **Last Validated:** 2026-03
* **Link:** https://www.gartner.com/en/security/topics/soc-architecture
