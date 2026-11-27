---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: dental practice customers and PHI
    text: Pearly offers a Business Associate Agreement (BAA) to our dental practice customers enumerating our respective obligations under HIPAA.
    type: Business Associate Agreement offered
  - framework: PCI-DSS
    issuer: Stripe PCI-certified auditor
    period: null
    report_access: unstated
    scope: payment card data processed via Stripe
    text: Stripe has been audited by a PCI-certified auditor and is certified to PCI Service Provider Level 1.
    type: Service Provider Level 1 certification (Stripe)
  trust_center:
    url: https://www.pearly.co/security
frameworks:
- HIPAA
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pearly
provenance_date: '2026-11-10'
provider_name: Pearly
provider_slug: pearly
slug: pearly-compliance
source_date: '2026-11-10'
source_filename: pearly-compliance.yml
source_heading: Compliance
source_page: https://www.pearly.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pearly\naid: pearly\nurl: https://www.pearly.co/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.pearly.co/security\nattestations:\n- framework: HIPAA\n  type: Business Associate Agreement offered\n  scope: dental practice customers and PHI\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pearly offers a Business Associate Agreement (BAA) to our dental practice customers enumerating our respective\n    obligations under HIPAA.\n- framework: PCI-DSS\n  type: Service Provider Level 1 certification (Stripe)\n  scope: payment card data processed via Stripe\n  period: null\n\
  \  issuer: Stripe PCI-certified auditor\n  report_access: unstated\n  text: Stripe has been audited by a PCI-certified auditor and is certified to PCI Service Provider Level 1.\n"
source_yaml_url: https://artifacts.apis.io/pearly/compliance/pearly-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Pearly's own page on 2026-11-10.
synthetic: false
tags:
- Dental
- Billing
- Revenue Cycle Management
- Software-as-a-Service
- Healthcare
---
