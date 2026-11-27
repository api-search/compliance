---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.bluenote.ai/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bluenote
provenance_date: '2026-11-09'
provider_name: Bluenote
provider_slug: bluenote
slug: bluenote-compliance
source_date: '2026-11-09'
source_filename: bluenote-compliance.yml
source_heading: Compliance
source_page: https://trust.bluenote.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bluenote\naid: bluenote\nurl: https://trust.bluenote.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.bluenote.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/bluenote/compliance/bluenote-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Bluenote's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Life Sciences
- Artificial Intelligence
- Regulatory
- Clinical Documentation
- Pharmaceuticals
- AI Agents
- Clinical Development
---
