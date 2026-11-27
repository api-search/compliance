---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: systems scanned quarterly via Qualys PCI Platform
    text: to ensure compliance with the security requirements of the card schemes
    type: card scheme security requirements compliance
  trust_center:
    url: https://www.trustpayments.com/security/
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trust Payments
provenance_date: '2026-11-10'
provider_name: Trust Payments
provider_slug: trust-payments
slug: trust-payments-compliance
source_date: '2026-11-10'
source_filename: trust-payments-compliance.yml
source_heading: Compliance
source_page: https://www.trustpayments.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trust Payments\naid: trust-payments\nurl: https://www.trustpayments.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.trustpayments.com/security/\nattestations:\n- framework: other\n  type: card scheme security requirements compliance\n  scope: systems scanned quarterly via Qualys PCI Platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: to ensure compliance with the security requirements of the card schemes\n"
source_yaml_url: https://artifacts.apis.io/trust-payments/compliance/trust-payments-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Trust Payments's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- Tokenization
- Subscription
- 3D Secure
- Point-of-Sale
- Webhook
- Payouts
---
