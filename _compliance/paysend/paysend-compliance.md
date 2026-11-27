---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS certified
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Paysend follows rules set by agencies including the FCA (UK), FinCEN (U.S.), PSD2 (EU), and GDPR
    type: regulatory compliance
  trust_center:
    url: https://paysend.com/blog/paysend-compliance-security-digital-money-transfers
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Paysend
provenance_date: '2026-11-10'
provider_name: Paysend
provider_slug: paysend
slug: paysend-compliance
source_date: '2026-11-10'
source_filename: paysend-compliance.yml
source_heading: Compliance
source_page: https://paysend.com/blog/paysend-compliance-security-digital-money-transfers
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Paysend\naid: paysend\nurl: https://paysend.com/blog/paysend-compliance-security-digital-money-transfers\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://paysend.com/blog/paysend-compliance-security-digital-money-transfers\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS certified\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Paysend follows rules set by agencies including the FCA (UK), FinCEN (U.S.), PSD2 (EU), and\
  \ GDPR\n"
source_yaml_url: https://artifacts.apis.io/paysend/compliance/paysend-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Paysend's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Cross-Border
- Money Transfer
- Payouts
- Payment Processing
- Foreign Exchange
- Remittances
- Fintech
- Cross-Border Payments
---
