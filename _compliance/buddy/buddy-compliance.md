---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type II certification
    type: Type II certification
  trust_center:
    url: https://buddy.works/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Buddy
provenance_date: '2026-11-09'
provider_name: Buddy
provider_slug: buddy
slug: buddy-compliance
source_date: '2026-11-09'
source_filename: buddy-compliance.yml
source_heading: Compliance
source_page: https://buddy.works/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Buddy\naid: buddy\nurl: https://buddy.works/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/buddy-trust-center.yml\ntrust_center:\n  url: https://buddy.works/security\nattestations:\n- framework: SOC2\n  type: Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type II certification\n"
source_yaml_url: https://artifacts.apis.io/buddy/compliance/buddy-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Buddy's own page on 2026-11-09.
synthetic: false
tags:
- Continuous Integration
- Developer Tools
- Public APIs
- A2A
---
