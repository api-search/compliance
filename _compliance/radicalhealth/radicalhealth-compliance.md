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
    text: HIPAA, SOC 2 Type II certified
    type: Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA, SOC 2 Type II certified
    type: certification
  trust_center:
    url: https://radicalhealth.ai/llms.txt
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Radical Health
provenance_date: '2026-11-10'
provider_name: Radical Health
provider_slug: radicalhealth
slug: radicalhealth-compliance
source_date: '2026-11-10'
source_filename: radicalhealth-compliance.yml
source_heading: Compliance
source_page: https://radicalhealth.ai/llms.txt
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Radical Health\naid: radicalhealth\nurl: https://radicalhealth.ai/llms.txt\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/radicalhealth-trust-center.yml\ntrust_center:\n  url: https://radicalhealth.ai/llms.txt\nattestations:\n- framework: SOC2\n  type: Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA, SOC 2 Type II certified\n- framework: HIPAA\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA, SOC 2 Type II certified\n"
source_yaml_url: https://artifacts.apis.io/radicalhealth/compliance/radicalhealth-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Radical Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Artificial Intelligence
- Clinical Trials
- Patient Care
- Digital Health
---
