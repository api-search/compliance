---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: patient health information
    text: Compliant with HIPAA to protect patient health information.
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 certified with ongoing compliance with rigorous security and privacy standards.
    type: certification
  - framework: other
    issuer: null
    period: since June 2026
    report_access: unstated
    scope: OASIS and Plan of Care Quality Review Service
    text: CHAP VERIFIED since June 2026.
    type: CHAP Verified status
  trust_center:
    url: https://www.ollihomehealth.ai/compliance
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Olli Health
provenance_date: '2026-11-10'
provider_name: Olli Health
provider_slug: olli-health
slug: olli-health-compliance
source_date: '2026-11-10'
source_filename: olli-health-compliance.yml
source_heading: Compliance
source_page: https://www.ollihomehealth.ai/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Olli Health\naid: olli-health\nurl: https://www.ollihomehealth.ai/compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.ollihomehealth.ai/compliance\nattestations:\n- framework: HIPAA\n  type: compliance statement\n  scope: patient health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant with HIPAA to protect patient health information.\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 certified with ongoing compliance with rigorous security and privacy standards.\n- framework:\
  \ other\n  type: CHAP Verified status\n  scope: OASIS and Plan of Care Quality Review Service\n  period: since June 2026\n  issuer: null\n  report_access: unstated\n  text: CHAP VERIFIED since June 2026.\n"
source_yaml_url: https://artifacts.apis.io/olli-health/compliance/olli-health-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Olli Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Medical Coding
- OASIS
- Artificial Intelligence
- Clinical Documentation
- Revenue Cycle
---
