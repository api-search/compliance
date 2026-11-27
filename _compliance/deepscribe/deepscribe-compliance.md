---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: DeepScribe platform
    text: DeepScribe's finalized 2024 SOC 2 Type II report remains available upon request here
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Audit Report
    type: HIPAA compliance
  trust_center:
    url: https://trust.deepscribe.ai/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DeepScribe
provenance_date: '2026-11-09'
provider_name: DeepScribe
provider_slug: deepscribe
slug: deepscribe-compliance
source_date: '2026-11-09'
source_filename: deepscribe-compliance.yml
source_heading: Compliance
source_page: https://trust.deepscribe.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DeepScribe\naid: deepscribe\nurl: https://trust.deepscribe.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.deepscribe.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: DeepScribe platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: DeepScribe's finalized 2024 SOC 2 Type II report remains available upon request here\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Audit Report\n"
source_yaml_url: https://artifacts.apis.io/deepscribe/compliance/deepscribe-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from DeepScribe's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Clinical Documentation
- Medical Scribe
- Ambient AI
- Speech Recognition
- Medical Coding
- HIPAA
- EHR Integration
- Oncology
- Cardiology
- Value-Based Care
- Enterprise Saas
---
