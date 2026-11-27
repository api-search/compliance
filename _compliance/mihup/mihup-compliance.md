---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: ISO 27001 certified
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: DPDP Act 2023 compliant
    type: regulatory compliance (India DPDP Act 2023)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: BFSI deployments
    text: RBI data-localization compliant for BFSI deployments
    type: regulatory compliance (RBI data localization, BFSI deployments)
  trust_center:
    url: https://mihup.ai/llms.txt
frameworks:
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mihup
provenance_date: '2026-11-10'
provider_name: Mihup
provider_slug: mihup
slug: mihup-compliance
source_date: '2026-11-10'
source_filename: mihup-compliance.yml
source_heading: Compliance
source_page: https://mihup.ai/llms.txt
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mihup\naid: mihup\nurl: https://mihup.ai/llms.txt\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mihup-trust-center.yml\ntrust_center:\n  url: https://mihup.ai/llms.txt\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 certified\n- framework: other\n  type: regulatory compliance (India DPDP Act 2023)\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DPDP Act 2023 compliant\n- framework: other\n  type: regulatory compliance (RBI data localization, BFSI deployments)\n\
  \  scope: BFSI deployments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RBI data-localization compliant for BFSI deployments\n"
source_yaml_url: https://artifacts.apis.io/mihup/compliance/mihup-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Mihup's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Voice AI
- Speech Recognition
- Speech Analytics
- Conversational AI
- Contact Center
- Automotive
- Natural Language Understanding
- Text-to-Speech
---
