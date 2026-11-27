---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001:2022 Certification
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II + HIPAA Report
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II + HIPAA Report
    type: compliance report
  trust_center:
    url: https://trust.navina.ai/
frameworks:
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Navina
provenance_date: '2026-11-10'
provider_name: Navina
provider_slug: navina
slug: navina-compliance
source_date: '2026-11-10'
source_filename: navina-compliance.yml
source_heading: Compliance
source_page: https://trust.navina.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Navina\naid: navina\nurl: https://trust.navina.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.navina.ai/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 Certification\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II + HIPAA Report\n- framework: HIPAA\n  type: compliance report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II + HIPAA Report\n"
source_yaml_url: https://artifacts.apis.io/navina/compliance/navina-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Navina's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical Decision Support
- Value-Based Care
- Risk Adjustment
- Electronic Health Records
- FHIR
- Interoperability
- Medical Coding
---
