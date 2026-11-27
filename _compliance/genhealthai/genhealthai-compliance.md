---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: AICPA SOC 2 HIPAA
    type: unstated
  - framework: HIPAA
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: AICPA SOC 2 HIPAA
    type: unstated
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.genhealth.ai/
    text: SOC 2 Type 2
    type: SOC 2 Type 2
  trust_center:
    url: https://genhealth.ai
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GenHealth.ai
provenance_date: '2026-11-09'
provider_name: GenHealth.ai
provider_slug: genhealthai
slug: genhealthai-compliance
source_date: '2026-11-09'
source_filename: genhealthai-compliance.yml
source_heading: Compliance
source_page: https://genhealth.ai
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GenHealth.ai\naid: genhealthai\nurl: https://genhealth.ai\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/genhealthai-trust-center.yml\n  sources:\n  - https://genhealth.ai\n  - https://trust.genhealth.ai/\ntrust_center:\n  url: https://genhealth.ai\nattestations:\n- framework: SOC2\n  type: unstated\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: AICPA SOC 2 HIPAA\n- framework: HIPAA\n  type: unstated\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: AICPA SOC 2 HIPAA\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n  source: https://trust.genhealth.ai/\n"
source_yaml_url: https://artifacts.apis.io/genhealthai/compliance/genhealthai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from GenHealth.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Artificial Intelligence
- Generative AI
- Prior Authorization
- Revenue Cycle Management
- FHIR
- HL7 Da Vinci
- Medical Coding
- Utilization Management
---
