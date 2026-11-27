---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II Report
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA Risk Assessment
    type: null
  trust_center:
    url: https://trust.openevidence.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OpenEvidence
provenance_date: '2026-11-10'
provider_name: OpenEvidence
provider_slug: openevidence
slug: openevidence-compliance
source_date: '2026-11-10'
source_filename: openevidence-compliance.yml
source_heading: Compliance
source_page: https://trust.openevidence.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OpenEvidence\naid: openevidence\nurl: https://trust.openevidence.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/openevidence-trust-center.yml\ntrust_center:\n  url: https://trust.openevidence.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Report\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA Risk Assessment\n"
source_yaml_url: https://artifacts.apis.io/openevidence/compliance/openevidence-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from OpenEvidence's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Clinical Decision Support
- Medical AI
- Generative AI
- Evidence-Based Medicine
- Search
- Voice
---
