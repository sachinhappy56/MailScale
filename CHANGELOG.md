# Changelog

All notable changes and release milestones for the **MailScale** platform will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0 Enterprise] - 2026-09-17

### Added
- **Standalone Windows Client**: Released self-contained, single-file desktop application (`releases/MailScale.EXE`) requiring zero external runtime installations.
- **Executive Telemetry Console**: Real-time deliverability rating (98.5% benchmark), active provider pool counters, daily quota consumption, and rapid campaign actions.
- **Multi-Provider Relay Pool**: Unified adapter layer supporting corporate SMTP relays, SendGrid, Mailjet, Brevo, Resend, and Amazon SES.
- **Dynamic Traffic Balancing**: Automated multi-relay load balancing and intelligent failover routing to preserve sender IP reputation.
- **Automated RFC 8058 Compliance**: Native header generation for 1-Click `List-Unsubscribe` complying with 2024+ industry sender mandates.
- **Audience Verification & Cleaner**: Integrated syntax validation, contact deduplication, and suppression list filtering.
- **Campaign & Template Studio**: Visual template authoring supporting dynamic subscriber token personalization and real-time previews.
- **Hardware Authorization Security**: Workstation-level machine licensing with out-of-the-box Free Evaluation Mode (500 sends/day).
- **Encrypted Local Vault**: Secure local credential storage for all SMTP and API relay tokens at rest.

### Security & Privacy
- Zero-cloud data footprint: all contact databases and message templates remain 100% on the local workstation.
- Automatic secret masking across all user interface views and operational logs.
