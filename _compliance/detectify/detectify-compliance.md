---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001
    type: null
  trust_center:
    url: https://detectify.com/
frameworks:
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: detectify
provenance_date: '2026-11-09'
provider_name: detectify
provider_slug: detectify
slug: detectify-compliance
source_date: '2026-11-09'
source_filename: detectify-compliance.yml
source_heading: Compliance
source_page: https://detectify.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: detectify\naid: detectify\nurl: https://detectify.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/detectify-trust-center.yml\ntrust_center:\n  url: https://detectify.com/\nattestations:\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001\n"
source_yaml_url: https://artifacts.apis.io/detectify/compliance/detectify-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from detectify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Attack Surface Management
- EASM
- Vulnerability Scanning
- DAST
- Application Security
- API Security
---
