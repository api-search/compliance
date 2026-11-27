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
    text: SOC 2 Type 2 Compliant
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: null
  trust_center:
    url: https://trust.brain.co/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Brain
provenance_date: '2026-11-09'
provider_name: Brain
provider_slug: brain
slug: brain-compliance
source_date: '2026-11-09'
source_filename: brain-compliance.yml
source_heading: Compliance
source_page: https://trust.brain.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Brain\naid: brain\nurl: https://trust.brain.co/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.brain.co/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Compliant\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/brain/compliance/brain-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Brain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Government
- Insurance
- Enterprise Software
- Automation
- Healthcare
---
