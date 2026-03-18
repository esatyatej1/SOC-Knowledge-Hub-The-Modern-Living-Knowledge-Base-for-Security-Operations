# Security Headers Monitoring

## Essential Headers
Configuring these headers correctly significantly reduces the attack surface for web applications.

| Header | Purpose | Example Value |
| :--- | :--- | :--- |
| **CSP** | Prevents XSS & Data Injection | `default-src 'self'` |
| **HSTS** | Forces HTTPS | `max-age=31536000` |
| **X-Frame-Options** | Prevents Clickjacking | `DENY` |
| **X-Content-Type** | Prevents MIME sniffing | `nosniff` |
| **Referrer-Policy** | Controls referrer data | `strict-origin-when-cross-origin` |

## How to Test
1. **[SecurityHeaders.com](https://securityheaders.com/)**: Quick A+ to F rating.
2. **[Mozilla Observatory](https://observatory.mozilla.org/)**: Modern analysis of web security posture.

---

### **[OWASP Secure Headers Project]**
* **Category:** Website Monitoring
* **Type:** Resource
* **Summary:** Comprehensive documentation on every security header and its value.
* **Link:** https://owasp.org/www-project-secure-headers/
