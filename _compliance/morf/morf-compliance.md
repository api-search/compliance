---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: Compliance listing
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2-II Certification Complete
    type: Type II certification
  trust_center:
    url: https://trust.morf.health/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Morf
provenance_date: '2026-11-10'
provider_name: Morf
provider_slug: morf
slug: morf-compliance
source_date: '2026-11-10'
source_filename: morf-compliance.yml
source_heading: Compliance
source_page: https://trust.morf.health/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Morf\naid: morf\nurl: https://trust.morf.health/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.morf.health/\nattestations:\n- framework: HIPAA\n  type: Compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: SOC2\n  type: Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2-II Certification Complete\n"
source_yaml_url: https://artifacts.apis.io/morf/compliance/morf-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Morf's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health IT
- Automation
- Integration
- iPaaS
- Webhook
- Electronic Health Records
- Patient Communication
- HIPAA
- Workflows
- Digital Health
---
