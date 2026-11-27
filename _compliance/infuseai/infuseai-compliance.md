---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type 1
    type: Type 1
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type 2
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.reccehq.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: InfuseAI
provenance_date: '2026-11-09'
provider_name: InfuseAI
provider_slug: infuseai
slug: infuseai-compliance
source_date: '2026-11-09'
source_filename: infuseai-compliance.yml
source_heading: Compliance
source_page: https://trust.reccehq.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: InfuseAI\naid: infuseai\nurl: https://trust.reccehq.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.reccehq.com/\nattestations:\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type 1\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type 2\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/infuseai/compliance/infuseai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from InfuseAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Data Quality
- Data Engineering
- dbt
- MLOps
- Analytics Engineering
- Developer Tools
- Open Source
- Artificial Intelligence
---
