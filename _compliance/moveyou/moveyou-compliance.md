---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security
    text: ISO/IEC 27001 certificate
    type: certificate
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy controls protecting PII
    text: ISO/IEC 27701 certificate
    type: certificate
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: quality management system
    text: ISO 9001 certificate
    type: certificate
  trust_center:
    url: https://moveyou.com/security/
frameworks:
- ISO27001
- ISO27701
- ISO9001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MoveYou
provenance_date: '2026-11-10'
provider_name: MoveYou
provider_slug: moveyou
slug: moveyou-compliance
source_date: '2026-11-10'
source_filename: moveyou-compliance.yml
source_heading: Compliance
source_page: https://moveyou.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MoveYou\naid: moveyou\nurl: https://moveyou.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/moveyou-trust-center.yml\ntrust_center:\n  url: https://moveyou.com/security/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: information security\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001 certificate\n- framework: ISO27701\n  type: certificate\n  scope: privacy controls protecting PII\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27701 certificate\n- framework: ISO9001\n  type: certificate\n  scope: quality\
  \ management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001 certificate\n"
source_yaml_url: https://artifacts.apis.io/moveyou/compliance/moveyou-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from MoveYou's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- Mobility
- Sustainability
---
