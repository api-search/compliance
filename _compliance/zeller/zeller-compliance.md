---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: All Zeller products
    text: All Zeller products are PCI Level 1 compliant.
    type: PCI Level 1 compliance / certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Zeller
    text: Full PCI-DSS certification.
    type: certification
  - framework: other
    issuer: Europay, Mastercard, Visa, American Express, EFTPOS and JCB
    period: null
    report_access: unstated
    scope: Zeller
    text: is certified by Europay, Mastercard, Visa, American Express, EFTPOS and JCB.
    type: card scheme certification
  trust_center:
    url: https://www.myzeller.com/au/security
frameworks:
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zeller
provenance_date: '2026-11-10'
provider_name: Zeller
provider_slug: zeller
slug: zeller-compliance
source_date: '2026-11-10'
source_filename: zeller-compliance.yml
source_heading: Compliance
source_page: https://www.myzeller.com/au/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zeller\naid: zeller\nurl: https://www.myzeller.com/au/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.myzeller.com/au/security\nattestations:\n- framework: PCI-DSS\n  type: PCI Level 1 compliance / certification\n  scope: All Zeller products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All Zeller products are PCI Level 1 compliant.\n- framework: PCI-DSS\n  type: certification\n  scope: Zeller\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full PCI-DSS certification.\n- framework: other\n  type: card scheme certification\n  scope: Zeller\n  period:\
  \ null\n  issuer: Europay, Mastercard, Visa, American Express, EFTPOS and JCB\n  report_access: unstated\n  text: is certified by Europay, Mastercard, Visa, American Express, EFTPOS and JCB.\n"
source_yaml_url: https://artifacts.apis.io/zeller/compliance/zeller-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Zeller's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Australia
- Payment Gateway
- Payment Processing
- Acquiring
- Merchant Services
- Point-of-Sale
- In-Person Payments
- Tap to Pay
- Small Business
---
