---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: PayPro Global as a Service Provider
    text: PayPro Global has been successfully certified as a PCI-DSS Level 1 Service Provider.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: PayPro Global
    text: Fulfills all the obligations for GDPR compliance
    type: compliance claim
  trust_center:
    url: https://payproglobal.com/compliance/
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayPro Global
provenance_date: '2026-11-10'
provider_name: PayPro Global
provider_slug: paypro-global
slug: paypro-global-compliance
source_date: '2026-11-10'
source_filename: paypro-global-compliance.yml
source_heading: Compliance
source_page: https://payproglobal.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayPro Global\naid: paypro-global\nurl: https://payproglobal.com/compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/paypro-global-trust-center.yml\ntrust_center:\n  url: https://payproglobal.com/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: PayPro Global as a Service Provider\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PayPro Global has been successfully certified as a PCI-DSS Level 1 Service Provider.\n- framework: GDPR\n  type: compliance claim\n  scope: PayPro Global\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Fulfills all the obligations for GDPR compliance\n"
source_yaml_url: https://artifacts.apis.io/paypro-global/compliance/paypro-global-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from PayPro Global's own page on 2026-11-10.
synthetic: false
tags:
- E-Commerce
- Merchant of Record
- Payments
- Software-as-a-Service
- Subscription Billing
- Tax Compliance
---
