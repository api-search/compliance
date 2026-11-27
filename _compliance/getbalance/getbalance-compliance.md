---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: PCI-certified auditor
    period: null
    report_access: unstated
    scope: Stripe as payment processor
    text: Our payment processing partner, Stripe, has been audited by a PCI-certified auditor and is certified to PCI Service Provider Level 1 .
    type: third-party processor certification
  trust_center:
    url: https://www.getbalance.com/legal/security-policy/
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Balance
provenance_date: '2026-11-09'
provider_name: Balance
provider_slug: getbalance
slug: getbalance-compliance
source_date: '2026-11-09'
source_filename: getbalance-compliance.yml
source_heading: Compliance
source_page: https://www.getbalance.com/legal/security-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Balance\naid: getbalance\nurl: https://www.getbalance.com/legal/security-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.getbalance.com/legal/security-policy/\nattestations:\n- framework: PCI-DSS\n  type: third-party processor certification\n  scope: Stripe as payment processor\n  period: null\n  issuer: PCI-certified auditor\n  report_access: unstated\n  text: Our payment processing partner, Stripe, has been audited by a PCI-certified auditor and is certified to\n    PCI Service Provider Level 1 .\n"
source_yaml_url: https://artifacts.apis.io/getbalance/compliance/getbalance-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Balance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- B2B Payments
- Trade Credit
- Buy Now Pay Later
- Accounts Receivable
- Financial Infrastructure
- Fintech
- Order-to-Cash
- Embedded Finance
- Marketplace
---
