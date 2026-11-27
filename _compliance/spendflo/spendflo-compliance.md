---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: SOC 2 Certified
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: ISO 27001 Certified
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: GDPR Compliant
    type: compliance
  trust_center:
    url: https://security.spendflo.com/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Spendflo
provenance_date: '2026-11-10'
provider_name: Spendflo
provider_slug: spendflo
slug: spendflo-compliance
source_date: '2026-11-10'
source_filename: spendflo-compliance.yml
source_heading: Compliance
source_page: https://security.spendflo.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Spendflo\naid: spendflo\nurl: https://security.spendflo.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/spendflo-trust-center.yml\ntrust_center:\n  url: https://security.spendflo.com/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n- framework: ISO27001\n  type: certification\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: GDPR\n  type: compliance\n  scope: not stated\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/spendflo/compliance/spendflo-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Spendflo's own page on 2026-11-10.
synthetic: false
tags:
- License Management
- Procurement
- SaaS Management
- Spend Management
- Usage Analytics
- Vendor Management
---
