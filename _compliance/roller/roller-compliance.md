---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Guest and transaction data stored on AWS infrastructure
    text: certified to SOC 2 standards
    type: null
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: compliant with PCI DSS
    type: null
  trust_center:
    url: https://www.roller.software/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ROLLER
provenance_date: '2026-11-10'
provider_name: ROLLER
provider_slug: roller
slug: roller-compliance
source_date: '2026-11-10'
source_filename: roller-compliance.yml
source_heading: Compliance
source_page: https://www.roller.software/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ROLLER\naid: roller\nurl: https://www.roller.software/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/roller-trust-center.yml\ntrust_center:\n  url: https://www.roller.software/security\nattestations:\n- framework: SOC2\n  type: null\n  scope: Guest and transaction data stored on AWS infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: certified to SOC 2 standards\n- framework: PCI-DSS\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: compliant with PCI DSS\n"
source_yaml_url: https://artifacts.apis.io/roller/compliance/roller-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ROLLER's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Venue Management
- Attractions
- Ticketing
- Booking
- Point-of-Sale
- Payments
- Leisure
- Reservations
- Webhook
---
