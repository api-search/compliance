---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: Auditors certified by the American Institute of CPAs
    period: null
    report_access: unstated
    scope: null
    text: PayIt is also SOC 1 Type 2 and SOC 2 Type 2 compliant.
    type: Type 2 attestation
  - framework: SOC2
    issuer: Auditors certified by the American Institute of CPAs
    period: null
    report_access: unstated
    scope: null
    text: PayIt is also SOC 1 Type 2 and SOC 2 Type 2 compliant.
    type: Type 2 attestation
  - framework: ISO27001
    issuer: The International Standards Organization
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 & 27018 Certified
    type: certification
  - framework: ISO27018
    issuer: The International Standards Organization
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 & 27018 Certified
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PayIt maintains DSS Level 1 compliance – the highest and most stringent.
    type: compliance (DSS Level 1)
  trust_center:
    url: https://payitgov.com/security-and-compliance/
frameworks:
- ISO27001
- ISO27018
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayIt
provenance_date: '2026-11-10'
provider_name: PayIt
provider_slug: payit
slug: payit-compliance
source_date: '2026-11-10'
source_filename: payit-compliance.yml
source_heading: Compliance
source_page: https://payitgov.com/security-and-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayIt\naid: payit\nurl: https://payitgov.com/security-and-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://payitgov.com/security-and-compliance/\nattestations:\n- framework: SOC1\n  type: Type 2 attestation\n  scope: null\n  period: null\n  issuer: Auditors certified by the American Institute of CPAs\n  report_access: unstated\n  text: PayIt is also SOC 1 Type 2 and SOC 2 Type 2 compliant.\n- framework: SOC2\n  type: Type 2 attestation\n  scope: null\n  period: null\n  issuer: Auditors certified by the American Institute of CPAs\n  report_access: unstated\n  text: PayIt is also SOC 1 Type\
  \ 2 and SOC 2 Type 2 compliant.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: The International Standards Organization\n  report_access: unstated\n  text: ISO 27001 & 27018 Certified\n- framework: ISO27018\n  type: certification\n  scope: null\n  period: null\n  issuer: The International Standards Organization\n  report_access: unstated\n  text: ISO 27001 & 27018 Certified\n- framework: PCI-DSS\n  type: compliance (DSS Level 1)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PayIt maintains DSS Level 1 compliance – the highest and most stringent.\n"
source_yaml_url: https://artifacts.apis.io/payit/compliance/payit-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from PayIt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Government
- GovTech
- Payments
- Digital Government
- Public Sector
- Citizen Experience
- DMV
---
