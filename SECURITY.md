# Security & Compliance Policy

MailScale is engineered with a defense-in-depth security model focused on credential protection, communication privacy, and delivery compliance. This policy outlines our security commitments, data handling practices, and vulnerability disclosure standards.

---

## 1. Supported Releases

| Version | Status | Security Maintenance |
| :--- | :--- | :--- |
| **1.0.x Enterprise** | Current Production | Active Security Updates & Patches |
| **< 1.0** | Deprecated | End of Life |

---

## 2. Core Security & Privacy Principles

### Local Data Sovereignty
- MailScale operates as a privacy-first workstation client. 
- Contact lists, subscriber personal data, audience segments, and campaign templates are stored strictly within your local environment.
- No subscriber records or campaign contents are ever uploaded to third-party tracking servers.

### Credential Protection at Rest
- All outbound gateway credentials, SMTP authentication passwords, and cloud API tokens are protected at rest within a local encrypted vault.
- Credentials are bound to local workstation security parameters and never exposed in cleartext.

### Transport Layer Security (TLS)
- All network interactions with external mail relays and cloud provider APIs enforce encrypted communication using **TLS 1.2 or TLS 1.3**.
- Unencrypted cleartext transmission over public networks is strictly barred.

### Secret Masking & Redaction
- Interactive user interfaces and execution logs automatically mask and redact sensitive tokens, bearer headers, and authentication keys.

### Deliverability & Anti-Abuse Integrity
- MailScale strictly adheres to international sender standards:
  - **RFC 8058 / RFC 2369**: Standardized 1-Click unsubscribe mechanics.
  - **RFC 5321 / RFC 5322**: Validated message format and transport specifications.
  - Features designed to bypass anti-abuse systems, falsify sender identities, or evade ISP reputation controls are strictly prohibited.

---

## 3. Reporting Security Issues

If you identify a security concern or potential vulnerability, we appreciate your responsible disclosure:

1. **Submission**: Report details via GitHub Security Advisories or to the designated project security maintainers.
2. **Details Requested**:
   - High-level summary of the issue.
   - Affected version and operating system environment.
   - Safe, non-destructive reproduction steps.
3. **Response Commitment**:
   - Acknowledgement within 48 business hours.
   - Regular status updates during remediation and patch validation.
