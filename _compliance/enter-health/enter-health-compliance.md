---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: since Aug 15, 2022
    report_access: unstated
    scope: null
    text: We have been SOC 2 Type 2 certified since Aug 15, 2022
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are HIPAA compliant and signing a BAA will ensure even stronger data controls.
    type: compliance statement
  trust_center:
    url: https://www.enter.health/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Romit
provenance_date: '2026-11-09'
provider_name: Romit
provider_slug: enter-health
slug: enter-health-compliance
source_date: '2026-11-09'
source_filename: enter-health-compliance.yml
source_heading: Compliance
source_page: https://www.enter.health/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Romit\naid: enter-health\nurl: https://www.enter.health/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.enter.health/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: since Aug 15, 2022\n  issuer: null\n  report_access: unstated\n  text: We have been SOC 2 Type 2 certified since Aug 15, 2022\n- framework: HIPAA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are HIPAA compliant and signing a BAA will ensure even stronger data controls.\n"
source_yaml_url: https://artifacts.apis.io/enter-health/compliance/enter-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Romit's own page on 2026-11-09.
synthetic: false
tags:
- Revenue Cycle Management
- Healthcare
- Artificial Intelligence
- Billing
- Claims
- Payments
---
