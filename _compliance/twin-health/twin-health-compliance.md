---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: on_request
    scope: Twin Health
    text: Twin is SOC2 Type 2 certified by AICPA. A copy of our SOC report is available to customers and partners upon request.
    type: Type 2 audit
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Twin Health
    text: Twin Health is HIPAA compliant.
    type: compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Twin Health
    text: Twin Health is SOC 2 Type 1 Certified and maintains an Information Security program
    type: Type 1 certification
  trust_center:
    url: https://usa.twinhealth.com/legal/security-and-compliance
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Twin Health
provenance_date: '2026-11-10'
provider_name: Twin Health
provider_slug: twin-health
slug: twin-health-compliance
source_date: '2026-11-10'
source_filename: twin-health-compliance.yml
source_heading: Compliance
source_page: https://usa.twinhealth.com/legal/security-and-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Twin Health\naid: twin-health\nurl: https://usa.twinhealth.com/legal/security-and-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://usa.twinhealth.com/legal/security-and-compliance\nattestations:\n- framework: SOC2\n  type: Type 2 audit\n  scope: Twin Health\n  period: null\n  issuer: AICPA\n  report_access: on_request\n  text: Twin is SOC2 Type 2 certified by AICPA. A copy of our SOC report is available to customers and partners\n    upon request.\n- framework: HIPAA\n  type: compliance\n  scope: Twin Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Twin Health is\
  \ HIPAA compliant.\n- framework: SOC2\n  type: Type 1 certification\n  scope: Twin Health\n  period: null\n  issuer: null\n  report_access: nda\n  text: Twin Health is SOC 2 Type 1 Certified and maintains an Information Security program\n"
source_yaml_url: https://artifacts.apis.io/twin-health/compliance/twin-health-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Twin Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Metabolic Health
- Digital Twin
- Diabetes
- Chronic Care
- Artificial Intelligence
- Health Plans
- Employer Benefits
---
