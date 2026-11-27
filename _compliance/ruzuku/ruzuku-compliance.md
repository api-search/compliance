---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Ruzuku data processing
    text: Ruzuku complies with GDPR requirements for data protection.
    type: self-stated compliance
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Stripe or PayPal payment processing
    text: processed securely by Stripe or PayPal — industry-leading payment processors with PCI DSS Level 1 certification (the highest level of payment security).
    type: processor certification
  trust_center:
    url: https://www.ruzuku.com/security
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ruzuku
provenance_date: '2026-11-10'
provider_name: Ruzuku
provider_slug: ruzuku
slug: ruzuku-compliance
source_date: '2026-11-10'
source_filename: ruzuku-compliance.yml
source_heading: Compliance
source_page: https://www.ruzuku.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ruzuku\naid: ruzuku\nurl: https://www.ruzuku.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ruzuku-trust-center.yml\ntrust_center:\n  url: https://www.ruzuku.com/security\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: Ruzuku data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ruzuku complies with GDPR requirements for data protection.\n- framework: PCI-DSS\n  type: processor certification\n  scope: Stripe or PayPal payment processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: processed securely by Stripe\
  \ or PayPal — industry-leading payment processors with PCI DSS Level 1 certification\n    (the highest level of payment security).\n"
source_yaml_url: https://artifacts.apis.io/ruzuku/compliance/ruzuku-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Ruzuku's own page on 2026-11-10.
synthetic: false
tags:
- Online Courses
- LMS
- Education
- Course Platform
- Zapier
- Gated
---
