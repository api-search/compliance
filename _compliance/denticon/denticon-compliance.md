---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: cloud-based software
    text: Our cloud-based software minimizes the risk of data breaches, ensuring compliance with HIPAA standards.
    type: compliance claim
  trust_center:
    url: https://www.planetdds.com/
frameworks:
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Denticon
provenance_date: '2026-11-09'
provider_name: Denticon
provider_slug: denticon
slug: denticon-compliance
source_date: '2026-11-09'
source_filename: denticon-compliance.yml
source_heading: Compliance
source_page: https://www.planetdds.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Denticon\naid: denticon\nurl: https://www.planetdds.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/denticon-trust-center.yml\ntrust_center:\n  url: https://www.planetdds.com/\nattestations:\n- framework: HIPAA\n  type: compliance claim\n  scope: cloud-based software\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our cloud-based software minimizes the risk of data breaches, ensuring compliance with HIPAA standards.\n"
source_yaml_url: https://artifacts.apis.io/denticon/compliance/denticon-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Denticon's own page on 2026-11-09.
synthetic: false
tags:
- Dental
- Practice Management
- Healthcare
- DSO
- Electronic Health Records
- Patient Data
- Revenue Cycle Management
- Partner API
---
