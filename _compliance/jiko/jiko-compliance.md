---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Jiko internal controls safeguarding security and privacy of customer information
    text: Jiko has achieved SOC 2 and PCI certifications and utilizes cloud-based infrastructure with robust data encryption.
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: secure handling of payment card data
    text: Meanwhile, PCI certification ensures the secure handling of payment card data.
    type: certification
  trust_center:
    url: https://www.jiko.com/trust-and-safety
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Jiko
provenance_date: '2026-11-09'
provider_name: Jiko
provider_slug: jiko
slug: jiko-compliance
source_date: '2026-11-09'
source_filename: jiko-compliance.yml
source_heading: Compliance
source_page: https://www.jiko.com/trust-and-safety
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Jiko\naid: jiko\nurl: https://www.jiko.com/trust-and-safety\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.jiko.com/trust-and-safety\nattestations:\n- framework: SOC2\n  type: certification\n  scope: Jiko internal controls safeguarding security and privacy of customer information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Jiko has achieved SOC 2 and PCI certifications and utilizes cloud-based infrastructure with robust data\n    encryption.\n- framework: PCI-DSS\n  type: certification\n  scope: secure handling of payment card data\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Meanwhile, PCI certification ensures the secure handling of payment card data.\n"
source_yaml_url: https://artifacts.apis.io/jiko/compliance/jiko-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Jiko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Payments
- Treasury
- Embedded Finance
- Fintech
- Cards
- Settlement
- Broker-Dealer
- Banking as a Service
---
