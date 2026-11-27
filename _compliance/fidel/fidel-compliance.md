---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: independent Qualified Security Assessors (QSAs)
    period: null
    report_access: unstated
    scope: handling of cardholder data
    text: Fidel API is PCI DSS Level 1 certified
    type: certification (Level 1), annual QSA audits
  trust_center:
    url: https://fidelapi.com/legal/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fidel
provenance_date: '2026-11-09'
provider_name: Fidel
provider_slug: fidel
slug: fidel-compliance
source_date: '2026-11-09'
source_filename: fidel-compliance.yml
source_heading: Compliance
source_page: https://fidelapi.com/legal/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fidel\naid: fidel\nurl: https://fidelapi.com/legal/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://fidelapi.com/legal/security\nattestations:\n- framework: PCI-DSS\n  type: certification (Level 1), annual QSA audits\n  scope: handling of cardholder data\n  period: null\n  issuer: independent Qualified Security Assessors (QSAs)\n  report_access: unstated\n  text: Fidel API is PCI DSS Level 1 certified\n"
source_yaml_url: https://artifacts.apis.io/fidel/compliance/fidel-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Fidel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Card Linking
- Transaction
- Fintech
- Embedded Finance
- Loyalty
- Rewards
- Webhook
- SDK
- Loyalty & Incentives
---
