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
    text: SOC II, Type 2
    type: SOC II, Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: HIPAA Compliant
  trust_center:
    url: https://murj.com/security/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Murj
provenance_date: '2026-11-10'
provider_name: Murj
provider_slug: murj
slug: murj-compliance
source_date: '2026-11-10'
source_filename: murj-compliance.yml
source_heading: Compliance
source_page: https://murj.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Murj\naid: murj\nurl: https://murj.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://murj.com/security/\nattestations:\n- framework: SOC2\n  type: SOC II, Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC II, Type 2\n- framework: HIPAA\n  type: HIPAA Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/murj/compliance/murj-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Murj's own page on 2026-11-10.
synthetic: false
tags:
- Cardiac Device Management
- Remote Patient Monitoring
- Heart Failure Monitoring
- Ambulatory Cardiac Monitoring
- Pulmonary Artery Pressure Monitoring
- Clinical Services
---
