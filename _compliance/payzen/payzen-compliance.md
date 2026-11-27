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
    text: Our commitment to your protection is validated by our SOC2 certification
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: healthcare data
    text: As a fully HIPAA compliant institution, we ensure the utmost confidentiality and security of your sensitive medical and personal information.
    type: compliance
  trust_center:
    url: https://payzen.com/payzen-compliance/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayZen
provenance_date: '2026-11-10'
provider_name: PayZen
provider_slug: payzen
slug: payzen-compliance
source_date: '2026-11-10'
source_filename: payzen-compliance.yml
source_heading: Compliance
source_page: https://payzen.com/payzen-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayZen\naid: payzen\nurl: https://payzen.com/payzen-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/payzen-trust-center.yml\ntrust_center:\n  url: https://payzen.com/payzen-compliance/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our commitment to your protection is validated by our SOC2 certification\n- framework: HIPAA\n  type: compliance\n  scope: healthcare data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: As a fully HIPAA compliant institution, we ensure the utmost\
  \ confidentiality and security of your sensitive\n    medical and personal information.\n"
source_yaml_url: https://artifacts.apis.io/payzen/compliance/payzen-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from PayZen's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Healthcare
- Patient Financing
- Revenue Cycle Management
- Lending
- Fintech
- Electronic Health Records
---
