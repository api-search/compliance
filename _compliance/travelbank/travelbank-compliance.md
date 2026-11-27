---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: TravelBank policies
    text: we’ve ensured that our policies fall in line with the General Data Protection Regulation (GDPR)
    type: policy alignment statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: TravelBank policies
    text: we have updated our policies to ensure compliance and maintain privacy and security for our customers
    type: compliance statement
  trust_center:
    url: https://travelbank.com/trust
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TravelBank
provenance_date: '2026-11-10'
provider_name: TravelBank
provider_slug: travelbank
slug: travelbank-compliance
source_date: '2026-11-10'
source_filename: travelbank-compliance.yml
source_heading: Compliance
source_page: https://travelbank.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TravelBank\naid: travelbank\nurl: https://travelbank.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://travelbank.com/trust\nattestations:\n- framework: GDPR\n  type: policy alignment statement\n  scope: TravelBank policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we’ve ensured that our policies fall in line with the General Data Protection Regulation (GDPR)\n- framework: CCPA\n  type: compliance statement\n  scope: TravelBank policies\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we have updated our policies to ensure compliance and maintain privacy\
  \ and security for our customers\n"
source_yaml_url: https://artifacts.apis.io/travelbank/compliance/travelbank-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from TravelBank's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Travel
- Expense Management
- Corporate Cards
- Fintech
- Travel Booking
---
