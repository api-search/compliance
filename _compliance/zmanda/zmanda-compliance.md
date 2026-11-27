---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: QRC
    period: continuous 12-month period
    report_access: unstated
    scope: security, availability, confidentiality trust principles
    text: BETSOL's SOC 2 Type II attestation verifies the operational effectiveness of our security controls over a continuous 12-month period.
    type: SOC 2 Type II attestation
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: BETSOL maintains ISO 27001 certification for our information security management system.
    type: ISO 27001 certification
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: product development, customer support, and service delivery
    text: Our ISO 9001 certification demonstrates BETSOL's commitment to consistent quality across product development, customer support, and service delivery.
    type: ISO 9001 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Zmanda Pro HIPAA-regulated environments
    text: Zmanda also executes business associate agreements (BAAs) with healthcare customers to support HIPAA-compliant backup and recovery environments.
    type: HIPAA support and business associate agreements
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: customers handling payment card data
    text: BETSOL maintains PCI DSS compliance to support customers handling payment card data.
    type: PCI DSS compliance
  trust_center:
    url: https://www.zmanda.com/trust-center/
frameworks:
- HIPAA
- ISO27001
- ISO9001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zmanda
provenance_date: '2026-11-10'
provider_name: Zmanda
provider_slug: zmanda
slug: zmanda-compliance
source_date: '2026-11-10'
source_filename: zmanda-compliance.yml
source_heading: Compliance
source_page: https://www.zmanda.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zmanda\naid: zmanda\nurl: https://www.zmanda.com/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zmanda-trust-center.yml\ntrust_center:\n  url: https://www.zmanda.com/trust-center/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation\n  scope: security, availability, confidentiality trust principles\n  period: continuous 12-month period\n  issuer: QRC\n  report_access: unstated\n  text: BETSOL's SOC 2 Type II attestation verifies the operational effectiveness of our security controls over\n    a continuous 12-month period.\n- framework: ISO27001\n  type: ISO 27001 certification\n\
  \  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: BETSOL maintains ISO 27001 certification for our information security management system.\n- framework: ISO9001\n  type: ISO 9001 certification\n  scope: product development, customer support, and service delivery\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our ISO 9001 certification demonstrates BETSOL's commitment to consistent quality across product development,\n    customer support, and service delivery.\n- framework: HIPAA\n  type: HIPAA support and business associate agreements\n  scope: Zmanda Pro HIPAA-regulated environments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zmanda also executes business associate agreements (BAAs) with healthcare customers to support HIPAA-compliant\n    backup and recovery environments.\n- framework: PCI-DSS\n  type: PCI DSS compliance\n  scope: customers handling payment card data\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: BETSOL maintains PCI DSS compliance to support customers handling payment card data.\n"
source_yaml_url: https://artifacts.apis.io/zmanda/compliance/zmanda-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Zmanda's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Backup
- Recovery
- Data Protection
- Disaster Recovery
- Cloud Backup
- Storage
- Enterprise Software
- Amanda
- Database Backup
---
