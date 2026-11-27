---
claim_count: 8
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Our ISO 27001 certification demonstrates our adherence to internationally recognized information security practices
    type: certification
  - framework: SOC1
    issuer: null
    period: null
    report_access: public
    scope: internal controls over financial reporting
    text: Our SOC 1 report is designed to address internal controls over financial reporting
    type: SOC 1 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: public
    scope: security, availability, processing integrity, confidentiality, and privacy of customer data
    text: Our SOC2 certification signifies that we’ve implemented rigorous controls to ensure the security, availability, processing integrity, confidentiality, and privacy of customer data
    type: SOC 2 Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: public
    scope: payment card information
    text: Our PCI DSS certification ensures the highest level of security for your payment card information.
    type: PCI DSS Level 1 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data
    text: We prioritize data protection, secure storage, and responsible data usage in accordance with GDPR guidelines.
    type: stated compliance
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: ICT risk management, incident reporting, resilience testing
    text: We are one of the early adopters of The Digital Operational Resilience Act (DORA)
    type: stated compliance
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: cloud security
    text: Payhawk is listed in the CSA Security Trust Assurance and Risk (STAR) registry
    type: CSA STAR Level 1 registry listing
  - framework: other
    issuer: null
    period: null
    report_access: public
    scope: software accounting practices, data integrity, traceability, secure document management
    text: Payhawk’s software has been independently audited in accordance with the German auditing standard IDW PS 880.
    type: IDW PS 880 independent audit
  trust_center:
    url: https://payhawk.com/trust
frameworks:
- CSA-STAR
- DORA
- GDPR
- ISO27001
- PCI-DSS
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Payhawk
provenance_date: '2026-11-10'
provider_name: Payhawk
provider_slug: payhawk
slug: payhawk-compliance
source_date: '2026-11-10'
source_filename: payhawk-compliance.yml
source_heading: Compliance
source_page: https://payhawk.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Payhawk\naid: payhawk\nurl: https://payhawk.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/payhawk-trust-center.yml\ntrust_center:\n  url: https://payhawk.com/trust\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Our ISO 27001 certification demonstrates our adherence to internationally recognized information security\n    practices\n- framework: SOC1\n  type: SOC 1 Type 2 report\n  scope: internal controls over financial reporting\n  period: null\n  issuer: null\n  report_access: public\n  text:\
  \ Our SOC 1 report is designed to address internal controls over financial reporting\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: security, availability, processing integrity, confidentiality, and privacy of customer data\n  period: null\n  issuer: null\n  report_access: public\n  text: Our SOC2 certification signifies that we’ve implemented rigorous controls to ensure the security, availability,\n    processing integrity, confidentiality, and privacy of customer data\n- framework: PCI-DSS\n  type: PCI DSS Level 1 certification\n  scope: payment card information\n  period: null\n  issuer: null\n  report_access: public\n  text: Our PCI DSS certification ensures the highest level of security for your payment card information.\n- framework: GDPR\n  type: stated compliance\n  scope: personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We prioritize data protection, secure storage, and responsible data usage in accordance with GDPR guidelines.\n- framework:\
  \ DORA\n  type: stated compliance\n  scope: ICT risk management, incident reporting, resilience testing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are one of the early adopters of The Digital Operational Resilience Act (DORA)\n- framework: CSA-STAR\n  type: CSA STAR Level 1 registry listing\n  scope: cloud security\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Payhawk is listed in the CSA Security Trust Assurance and Risk (STAR) registry\n- framework: other\n  type: IDW PS 880 independent audit\n  scope: software accounting practices, data integrity, traceability, secure document management\n  period: null\n  issuer: null\n  report_access: public\n  text: Payhawk’s software has been independently audited in accordance with the German auditing standard IDW PS\n    880.\n"
source_yaml_url: https://artifacts.apis.io/payhawk/compliance/payhawk-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Payhawk's own page on 2026-11-10.
synthetic: false
tags:
- Spend Management
- Corporate Cards
- Expense Management
- Invoice Management
- Budget Controls
- ERP Integration
- Accounts Payable
- Fintech
- Finance Automation
- Webhook
---
