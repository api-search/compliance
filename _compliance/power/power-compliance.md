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
    text: We are HIPAA and SOC 2 compliant.
    type: compliance claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are HIPAA and SOC 2 compliant.
    type: compliance claim
  trust_center:
    url: https://www.withpower.com/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Power
provenance_date: '2026-11-10'
provider_name: Power
provider_slug: power
slug: power-compliance
source_date: '2026-11-10'
source_filename: power-compliance.yml
source_heading: Compliance
source_page: https://www.withpower.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Power\naid: power\nurl: https://www.withpower.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/power-trust-center.yml\ntrust_center:\n  url: https://www.withpower.com/security\nattestations:\n- framework: HIPAA\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are HIPAA and SOC 2 compliant.\n- framework: SOC2\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are HIPAA and SOC 2 compliant.\n"
source_yaml_url: https://artifacts.apis.io/power/compliance/power-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Power's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Clinical Trials
- Healthcare
- Clinical Research
- Patient Matching
- Health
---
