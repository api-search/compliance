---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Certified
    type: certified
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliant
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 v2022 Certified
    type: certified
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliant
  trust_center:
    url: https://trust.ctgt.ai/
frameworks:
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CTGT
provenance_date: '2026-11-09'
provider_name: CTGT
provider_slug: ctgt
slug: ctgt-compliance
source_date: '2026-11-09'
source_filename: ctgt-compliance.yml
source_heading: Compliance
source_page: https://trust.ctgt.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CTGT\naid: ctgt\nurl: https://trust.ctgt.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.ctgt.ai/\nattestations:\n- framework: SOC2\n  type: certified\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n- framework: GDPR\n  type: compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: ISO27001\n  type: certified\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 v2022 Certified\n- framework: HIPAA\n  type: compliant\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/ctgt/compliance/ctgt-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from CTGT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise AI
- Compliance
- Policy Engine
- RAG
- Mission-Critical
---
