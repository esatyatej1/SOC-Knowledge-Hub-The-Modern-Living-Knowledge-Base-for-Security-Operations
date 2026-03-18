# SSL/TLS Certificate Monitoring

## Why Monitor SSL?
Expired certificates cause downtime. Weak protocols (TLS 1.0/1.1) cause security vulnerabilities.

## Core Checks
1. **Expiry Date:** Monitoring 30, 14, and 7 days before expiry.
2. **Chain Validation:** Ensuring the intermediate and root CA links are intact.
3. **Protocol Support:** Disabling SSLv2, SSLv3, TLS 1.0, and TLS 1.1.
4. **Cipher Suites:** Ensuring forward secrecy (PFS) is enabled.

## Tool Recommendations
- **[SSL Labs (Qualys)](https://www.ssllabs.com/ssltest/)**: The industry standard for web server analysis.
- **[Hardentools](https://github.com/securityscorecard/ssl-validator)**: Automated validation of SSL health.
- **[Let's Encrypt](https://letsencrypt.org/)**: For automated issuance and renewal.

---

### **[Mozilla SSL Configuration Generator]**
* **Category:** Website Monitoring
* **Type:** Tool
* **Summary:** Helps generate secure server configurations for Apache, Nginx, and more.
* **Link:** https://ssl-config.mozilla.org/
