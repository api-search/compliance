---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: we’re PCI compliant (meaning your credit card info is totally secure)
    type: PCI compliance
  trust_center:
    url: https://www.hoteltonight.com/terms-of-use/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hotel Tonight
provenance_date: '2026-11-09'
provider_name: Hotel Tonight
provider_slug: hotel-tonight
slug: hotel-tonight-compliance
source_date: '2026-11-09'
source_filename: hotel-tonight-compliance.yml
source_heading: Compliance
source_page: https://www.hoteltonight.com/terms-of-use/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hotel Tonight\naid: hotel-tonight\nurl: https://www.hoteltonight.com/terms-of-use/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.hoteltonight.com/terms-of-use/security\nattestations:\n- framework: PCI-DSS\n  type: PCI compliance\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we’re PCI compliant (meaning your credit card info is totally secure)\n"
source_yaml_url: https://artifacts.apis.io/hotel-tonight/compliance/hotel-tonight-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Hotel Tonight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Hotels
- Booking
- Hospitality
- Mobile
- Airbnb
---
