---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment processing environment
    text: PCI DSS Level 1 certified
    type: certification
  - framework: other
    issuer: PayNet Malaysia
    period: null
    report_access: unstated
    scope: DuitNow payments integration
    text: Certified by PayNet Malaysia to integrate DuitNow payments
    type: system integrator certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Pekeliling Perbendaharaan Malaysia PS 2.1
    text: Pekeliling Perbendaharaan Malaysia PS 2.1 Compliant
    type: compliance with government standard
  trust_center:
    url: https://main.billplz.com/security
frameworks:
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Billplz
provenance_date: '2026-11-09'
provider_name: Billplz
provider_slug: billplz
slug: billplz-compliance
source_date: '2026-11-09'
source_filename: billplz-compliance.yml
source_heading: Compliance
source_page: https://main.billplz.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Billplz\naid: billplz\nurl: https://main.billplz.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/billplz-trust-center.yml\ntrust_center:\n  url: https://main.billplz.com/security\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: payment processing environment\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Level 1 certified\n- framework: other\n  type: system integrator certification\n  scope: DuitNow payments integration\n  period: null\n  issuer: PayNet Malaysia\n  report_access: unstated\n  text: Certified by PayNet Malaysia to integrate\
  \ DuitNow payments\n- framework: other\n  type: compliance with government standard\n  scope: Pekeliling Perbendaharaan Malaysia PS 2.1\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pekeliling Perbendaharaan Malaysia PS 2.1 Compliant\n"
source_yaml_url: https://artifacts.apis.io/billplz/compliance/billplz-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Billplz's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Public APIs
---
