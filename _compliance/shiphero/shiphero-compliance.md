---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ShipHero is SOC 2 Type 2 audited, attested, and maintain a rigorous business continuity program.
    type: Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are GDPR compliant
    type: compliance statement
  trust_center:
    url: https://www.shiphero.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ShipHero
provenance_date: '2026-11-10'
provider_name: ShipHero
provider_slug: shiphero
slug: shiphero-compliance
source_date: '2026-11-10'
source_filename: shiphero-compliance.yml
source_heading: Compliance
source_page: https://www.shiphero.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ShipHero\naid: shiphero\nurl: https://www.shiphero.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/shiphero-trust-center.yml\ntrust_center:\n  url: https://www.shiphero.com/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ShipHero is SOC 2 Type 2 audited, attested, and maintain a rigorous business continuity program.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/shiphero/compliance/shiphero-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ShipHero's own page on 2026-11-10.
synthetic: false
tags:
- Warehouse Management
- Fulfillment
- E-Commerce
- GraphQL
- Inventory
- Order
- Shipments
- 3PL
- Logistics
---
