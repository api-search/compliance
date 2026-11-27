---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Tilda Research, Inc.
    text: SOC 2 Type II Report
    type: Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Opinion letter
    type: Opinion letter
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Audit Report
    type: Audit report
  trust_center:
    url: https://trust.tilda.bio/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tilda Research
provenance_date: '2026-11-10'
provider_name: Tilda Research
provider_slug: tilda
slug: tilda-compliance
source_date: '2026-11-10'
source_filename: tilda-compliance.yml
source_heading: Compliance
source_page: https://trust.tilda.bio/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tilda Research\naid: tilda\nurl: https://trust.tilda.bio/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.tilda.bio/\nattestations:\n- framework: SOC2\n  type: Type II report\n  scope: Tilda Research, Inc.\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Report\n- framework: HIPAA\n  type: Opinion letter\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Opinion letter\n- framework: GDPR\n  type: Audit report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Audit Report\n"
source_yaml_url: https://artifacts.apis.io/tilda/compliance/tilda-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Tilda Research's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Clinical Trials
- Clinical Research
- Artificial Intelligence
- AI Agents
- Healthcare
- Life Sciences
- Drug Development
---
