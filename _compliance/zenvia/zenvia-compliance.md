---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001:2022 Certificate
    type: certificate
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Zenvia - PCI-DSS 4.0.1
    type: null
  trust_center:
    url: https://trust.zenvia.com/
frameworks:
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zenvia
provenance_date: '2026-11-10'
provider_name: Zenvia
provider_slug: zenvia
slug: zenvia-compliance
source_date: '2026-11-10'
source_filename: zenvia-compliance.yml
source_heading: Compliance
source_page: https://trust.zenvia.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zenvia\naid: zenvia\nurl: https://trust.zenvia.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.zenvia.com/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 Certificate\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Zenvia - PCI-DSS 4.0.1\n"
source_yaml_url: https://artifacts.apis.io/zenvia/compliance/zenvia-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Zenvia's own page on 2026-11-10.
synthetic: false
tags:
- Customer Cloud
- WhatsApp
- Customer Experience
---
