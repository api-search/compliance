---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: All payment transactions
    text: All payment transactions follow PCI DSS Level 1 standards — the highest level of payment security — to ensure secure handling of cardholder data.
    type: PCI DSS Level 1 compliant payments
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Patient data across payment, messaging, and communication workflows
    text: Patient data processed through Tabz — across payment, messaging, and communication workflows — is handled in accordance with HIPAA's Privacy and Security Rules.
    type: HIPAA-ready infrastructure
  trust_center:
    url: https://runontabz.com/company/security
frameworks:
- HIPAA
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tabz
provenance_date: '2026-11-10'
provider_name: Tabz
provider_slug: tabz
slug: tabz-compliance
source_date: '2026-11-10'
source_filename: tabz-compliance.yml
source_heading: Compliance
source_page: https://runontabz.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tabz\naid: tabz\nurl: https://runontabz.com/company/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://runontabz.com/company/security\nattestations:\n- framework: PCI-DSS\n  type: PCI DSS Level 1 compliant payments\n  scope: All payment transactions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All payment transactions follow PCI DSS Level 1 standards — the highest level of payment security — to ensure\n    secure handling of cardholder data.\n- framework: HIPAA\n  type: HIPAA-ready infrastructure\n  scope: Patient data across payment, messaging, and communication workflows\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Patient data processed through Tabz — across payment, messaging, and communication workflows — is handled\n    in accordance with HIPAA's Privacy and Security Rules.\n"
source_yaml_url: https://artifacts.apis.io/tabz/compliance/tabz-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Tabz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pharmacy
- Payments
- Checkout
- Commerce
- Healthcare
---
