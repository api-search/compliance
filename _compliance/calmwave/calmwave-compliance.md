---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: HIPAA
  trust_center:
    url: https://trust.calmwave.ai/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CalmWave
provenance_date: '2026-11-09'
provider_name: CalmWave
provider_slug: calmwave
slug: calmwave-compliance
source_date: '2026-11-09'
source_filename: calmwave-compliance.yml
source_heading: Compliance
source_page: https://trust.calmwave.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CalmWave\naid: calmwave\nurl: https://trust.calmwave.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.calmwave.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/calmwave/compliance/calmwave-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from CalmWave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Data Platform
- Patient Safety
- Real-Time Analytics
---
