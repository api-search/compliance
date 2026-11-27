---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Cardholder data handling
    text: PayCargo complies with the Payment Card Industry Data Security Standard (PCI DSS), helping ensure that cardholder data is securely handled and protected.
    type: Compliance statement
  - framework: SOC1
    issuer: null
    period: null
    report_access: on_request
    scope: Controls over financial reporting, internal processes, and transaction security
    text: PayCargo is SOC 1 Type 2 certified, ensuring strong controls over financial reporting, internal processes, and transaction security.
    type: SOC 1 Type 2 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Personal data privacy practices
    text: PayCargo implements data privacy practices aligned with the EU General Data Protection Regulation (GDPR) globally
    type: Compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California consumer personal data
    text: We comply with the California Consumer Privacy Act (CCPA), empowering California residents with control over their personal data.
    type: Compliance statement
  trust_center:
    url: https://paycargo.com/security-compliance/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC1
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayCargo
provenance_date: '2026-11-10'
provider_name: PayCargo
provider_slug: paycargo-llc
slug: paycargo-llc-compliance
source_date: '2026-11-10'
source_filename: paycargo-llc-compliance.yml
source_heading: Compliance
source_page: https://paycargo.com/security-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayCargo\naid: paycargo-llc\nurl: https://paycargo.com/security-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://paycargo.com/security-compliance/\nattestations:\n- framework: PCI-DSS\n  type: Compliance statement\n  scope: Cardholder data handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PayCargo complies with the Payment Card Industry Data Security Standard (PCI DSS), helping ensure that cardholder\n    data is securely handled and protected.\n- framework: SOC1\n  type: SOC 1 Type 2 certification\n  scope: Controls over financial reporting, internal processes,\
  \ and transaction security\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PayCargo is SOC 1 Type 2 certified, ensuring strong controls over financial reporting, internal processes,\n    and transaction security.\n- framework: GDPR\n  type: Compliance statement\n  scope: Personal data privacy practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PayCargo implements data privacy practices aligned with the EU General Data Protection Regulation (GDPR)\n    globally\n- framework: CCPA\n  type: Compliance statement\n  scope: California consumer personal data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with the California Consumer Privacy Act (CCPA), empowering California residents with control\n    over their personal data.\n"
source_yaml_url: https://artifacts.apis.io/paycargo-llc/compliance/paycargo-llc-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from PayCargo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Freight
- Logistics
- Supply Chain
- Fintech
- Accounts Payable
- Shipping
---
