---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: not stated
    text: Ebury ISO 27001 Certificate Request Access
    type: certificate
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance ISO 27001 PCI DSS GDPR SWIFT CSP
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance ISO 27001 PCI DSS GDPR SWIFT CSP
    type: null
  trust_center:
    url: https://trust.ebury.com/
frameworks:
- GDPR
- ISO27001
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ebury
provenance_date: '2026-11-09'
provider_name: Ebury
provider_slug: ebury
slug: ebury-compliance
source_date: '2026-11-09'
source_filename: ebury-compliance.yml
source_heading: Compliance
source_page: https://trust.ebury.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ebury\naid: ebury\nurl: https://trust.ebury.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.ebury.com/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Ebury ISO 27001 Certificate Request Access\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance ISO 27001 PCI DSS GDPR SWIFT CSP\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance ISO 27001\
  \ PCI DSS GDPR SWIFT CSP\n"
source_yaml_url: https://artifacts.apis.io/ebury/compliance/ebury-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ebury's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- 'Internationalapis: []'
---
