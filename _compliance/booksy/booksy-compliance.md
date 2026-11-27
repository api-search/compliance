---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS 4.0.1
    type: PCI DSS 4.0.1 compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR compliance
  trust_center:
    url: https://trust.booksy.com/
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Booksy
provenance_date: '2026-11-09'
provider_name: Booksy
provider_slug: booksy
slug: booksy-compliance
source_date: '2026-11-09'
source_filename: booksy-compliance.yml
source_heading: Compliance
source_page: https://trust.booksy.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Booksy\naid: booksy\nurl: https://trust.booksy.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.booksy.com/\nattestations:\n- framework: PCI-DSS\n  type: PCI DSS 4.0.1 compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS 4.0.1\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/booksy/compliance/booksy-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Booksy's own page on 2026-11-09.
synthetic: false
tags:
- Beauty
- Wellness
- Booking
- Appointments
- Scheduling
- Marketplace
- Salon
- Barbershops
- Spas
- Payments
- Small Business
- Webhook
---
