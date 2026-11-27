---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, processing integrity, confidentiality, and privacy
    text: NDA required.
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Full compliance with EU General Data Protection Regulation.
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: US customer data protection and privacy rights
    text: California Consumer Privacy Act compliance for US customer data protection and privacy rights.
    type: compliance statement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: secure credit card processing
    text: Payment Card Industry Data Security Standard compliance for secure credit card processing.
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: healthcare customers
    text: Health Insurance Portability and Accountability Act compliance available for healthcare customers.
    type: BAA available
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: all SMS and voice communications
    text: Telephone Consumer Protection Act compliance for all SMS and voice communications.
    type: compliance statement (TCPA)
  trust_center:
    url: https://chargezen.com/trust
frameworks:
- CCPA
- GDPR
- HIPAA
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: chargezen-com
provenance_date: '2026-11-09'
provider_name: chargezen-com
provider_slug: chargezen-com
slug: chargezen-com-compliance
source_date: '2026-11-09'
source_filename: chargezen-com-compliance.yml
source_heading: Compliance
source_page: https://chargezen.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: chargezen-com\naid: chargezen-com\nurl: https://chargezen.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://chargezen.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: security, availability, processing integrity, confidentiality, and privacy\n  period: null\n  issuer: null\n  report_access: nda\n  text: NDA required.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full compliance with EU General Data Protection Regulation.\n- framework: CCPA\n  type: compliance statement\n\
  \  scope: US customer data protection and privacy rights\n  period: null\n  issuer: null\n  report_access: unstated\n  text: California Consumer Privacy Act compliance for US customer data protection and privacy rights.\n- framework: PCI-DSS\n  type: compliance statement\n  scope: secure credit card processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Payment Card Industry Data Security Standard compliance for secure credit card processing.\n- framework: HIPAA\n  type: BAA available\n  scope: healthcare customers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Health Insurance Portability and Accountability Act compliance available for healthcare customers.\n- framework: other\n  type: compliance statement (TCPA)\n  scope: all SMS and voice communications\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Telephone Consumer Protection Act compliance for all SMS and voice communications.\n"
source_yaml_url: https://artifacts.apis.io/chargezen-com/compliance/chargezen-com-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from chargezen-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
