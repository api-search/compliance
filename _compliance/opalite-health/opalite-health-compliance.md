---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Every conversation is treated as PHI
    text: HIPAA compliant
    type: compliance claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security practices
    text: SOC 2 Type II
    type: Type II audit
  trust_center:
    url: https://opalitehealth.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Opalite Health
provenance_date: '2026-11-10'
provider_name: Opalite Health
provider_slug: opalite-health
slug: opalite-health-compliance
source_date: '2026-11-10'
source_filename: opalite-health-compliance.yml
source_heading: Compliance
source_page: https://opalitehealth.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Opalite Health\naid: opalite-health\nurl: https://opalitehealth.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://opalitehealth.com/security\nattestations:\n- framework: HIPAA\n  type: compliance claim\n  scope: Every conversation is treated as PHI\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant\n- framework: SOC2\n  type: Type II audit\n  scope: Security practices\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n"
source_yaml_url: https://artifacts.apis.io/opalite-health/compliance/opalite-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Opalite Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Interpretation
- Artificial Intelligence
- Language Access
- Translation
- HIPAA
- Health Equity
- Digital Health
---
