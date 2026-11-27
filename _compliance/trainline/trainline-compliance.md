---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: merchant and service provider
    text: Trainline are PCI Level 1 compliant both as a merchant and as a service provider
    type: Level 1 compliance
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 (Information Security Management Systems) certified.
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 22301 (Business Continuity Management Systems)
    type: ISO 22301 certification (business continuity management)
  trust_center:
    url: https://www.thetrainline.com/terms/security
frameworks:
- ISO27001
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trainline
provenance_date: '2026-11-10'
provider_name: Trainline
provider_slug: trainline
slug: trainline-compliance
source_date: '2026-11-10'
source_filename: trainline-compliance.yml
source_heading: Compliance
source_page: https://www.thetrainline.com/terms/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trainline\naid: trainline\nurl: https://www.thetrainline.com/terms/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.thetrainline.com/terms/security\nattestations:\n- framework: PCI-DSS\n  type: Level 1 compliance\n  scope: merchant and service provider\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Trainline are PCI Level 1 compliant both as a merchant and as a service provider\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 (Information Security Management Systems) certified.\n\
  - framework: other\n  type: ISO 22301 certification (business continuity management)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 22301 (Business Continuity Management Systems)\n"
source_yaml_url: https://artifacts.apis.io/trainline/compliance/trainline-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Trainline's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Rail
- United Kingdom
- Europe
- Booking
- Ticketing
- Distribution
- OTA
- Corporate Travel
---
