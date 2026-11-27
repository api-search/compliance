---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Bankjoy client data controls (security, availability, processing integrity, confidentiality, privacy)
    text: SOC 2 Type II is a rigorous security audit that evaluates our internal controls and processes over an extended period.
    type: SOC 2 Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: handling, processing, and storing credit card information
    text: Payment Card Industry Data Security Standard (PCI DSS) compliance ensures that Bankjoy meets the strict security requirements for handling, processing, and storing credit card information.
    type: PCI DSS compliance
  trust_center:
    url: https://bankjoy.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bankjoy
provenance_date: '2026-11-09'
provider_name: Bankjoy
provider_slug: bankjoy
slug: bankjoy-compliance
source_date: '2026-11-09'
source_filename: bankjoy-compliance.yml
source_heading: Compliance
source_page: https://bankjoy.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bankjoy\naid: bankjoy\nurl: https://bankjoy.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://bankjoy.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Bankjoy client data controls (security, availability, processing integrity, confidentiality, privacy)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II is a rigorous security audit that evaluates our internal controls and processes over an extended\n    period.\n- framework: PCI-DSS\n  type: PCI DSS compliance\n  scope: handling, processing, and storing credit card information\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Payment Card Industry Data Security Standard (PCI DSS) compliance ensures that Bankjoy meets the strict\n    security requirements for handling, processing, and storing credit card information.\n"
source_yaml_url: https://artifacts.apis.io/bankjoy/compliance/bankjoy-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Bankjoy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Digital Banking
- Banking
- Credit Union
- Community Banks
- Financial Services
- Account Opening
- Lending
---
