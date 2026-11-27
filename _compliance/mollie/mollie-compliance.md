---
api_specs:
- filename: mollie-openapi-original.yml
  format: yaml
  label: Mollie API
  slug: mollie-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mollie/openapi/mollie-openapi-original.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality controls
    text: Our security, availability, and confidentiality controls are independently assessed against the AICPA's Trust Services Criteria, providing assurance of their effectiveness.
    type: SOC 2 Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: card payment processing
    text: We meet the highest level of security for processing card payments, a standard that we can prove with our Attestation of Compliance (AoC).
    type: Attestation of Compliance (AoC)
  - framework: other
    issuer: external auditor
    period: null
    report_access: unstated
    scope: operational controls
    text: Our operational controls are audited annually by an external auditor, providing independent assurance of our integrity.
    type: ISAE 3402 Type 2
  trust_center:
    url: https://www.mollie.com/security
frameworks:
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mollie
provenance_date: '2026-11-10'
provider_name: Mollie
provider_slug: mollie
slug: mollie-compliance
source_date: '2026-11-10'
source_filename: mollie-compliance.yml
source_heading: Compliance
source_page: https://www.mollie.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mollie\naid: mollie\nurl: https://www.mollie.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.mollie.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our security, availability, and confidentiality controls are independently assessed against the AICPA's\n    Trust Services Criteria, providing assurance of their effectiveness.\n- framework: PCI-DSS\n  type: Attestation of Compliance (AoC)\n  scope: card payment processing\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: We meet the highest level of security for processing card payments, a standard that we can prove with our\n    Attestation of Compliance (AoC).\n- framework: other\n  type: ISAE 3402 Type 2\n  scope: operational controls\n  period: null\n  issuer: external auditor\n  report_access: unstated\n  text: Our operational controls are audited annually by an external auditor, providing independent assurance of\n    our integrity.\n"
source_yaml_url: https://artifacts.apis.io/mollie/compliance/mollie-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Mollie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Financial Services
- Checkout
- E-Commerce
- Subscription
- Point-of-Sale
- Europe
- Netherlands
- Payment Processing
---
