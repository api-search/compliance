---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: UK GDPR and Data Protection Act 2018 compliance of the portal
    text: Full compliance with UK GDPR & Data Protection Act 2018
    type: self-stated compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Card payments, processed via Stripe's certified infrastructure
    text: PCI DSS compliant via Stripe's certified infrastructure.
    type: self-stated compliance
  trust_center:
    url: https://axel.trade/security
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: axel-trade
provenance_date: '2026-11-09'
provider_name: axel-trade
provider_slug: axel-trade
slug: axel-trade-compliance
source_date: '2026-11-09'
source_filename: axel-trade-compliance.yml
source_heading: Compliance
source_page: https://axel.trade/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: axel-trade\naid: axel-trade\nurl: https://axel.trade/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://axel.trade/security\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: UK GDPR and Data Protection Act 2018 compliance of the portal\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full compliance with UK GDPR & Data Protection Act 2018\n- framework: PCI-DSS\n  type: self-stated compliance\n  scope: Card payments, processed via Stripe's certified infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS compliant via\
  \ Stripe's certified infrastructure.\n"
source_yaml_url: https://artifacts.apis.io/axel-trade/compliance/axel-trade-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from axel-trade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Tax
- Accounting
- Software
- United Kingdom
---
