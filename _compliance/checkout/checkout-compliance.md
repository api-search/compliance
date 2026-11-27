---
api_specs:
- filename: checkout-openapi-generated.yml
  format: yaml
  label: Checkout API
  slug: checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/_ae-authored/checkout-openapi-generated.yml
- filename: checkout-checkout-api-api-openapi.yml
  format: yaml
  label: Checkout Checkout API
  slug: checkout-checkout-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-checkout-api-api-openapi.yml
- filename: checkout-connect-api-openapi.yml
  format: yaml
  label: Checkout Connect API
  slug: checkout-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-connect-api-openapi.yml
- filename: checkout-payments-api-openapi.yml
  format: yaml
  label: Checkout Payments API
  slug: checkout-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkout/openapi/checkout-payments-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type II
    type: Type II
  - framework: SOC2
    issuer: null
    period: June 1, 2024 - November 30, 2024
    report_access: unstated
    scope: security, availability, and confidentiality of customer data
    text: 'SOC 2 Type II Certification: June 1, 2024 - November 30, 2024'
    type: Type II
  - framework: PCI-DSS
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: Checkout.com has successfully certified for PCI DSS as a Level 1 Service Provider in 2025!
    type: Level 1 Service Provider
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Checkout.com has recertified for Cyber Essentials+
    type: Cyber Essentials Plus
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: null
  trust_center:
    url: https://trust.checkout.com/
frameworks:
- CCPA
- CyberEssentials
- GDPR
- ISO27001
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Checkout
provenance_date: '2026-11-09'
provider_name: Checkout
provider_slug: checkout
slug: checkout-compliance
source_date: '2026-11-09'
source_filename: checkout-compliance.yml
source_heading: Compliance
source_page: https://trust.checkout.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Checkout\naid: checkout\nurl: https://trust.checkout.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.checkout.com/\nattestations:\n- framework: SOC1\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type II\n- framework: SOC2\n  type: Type II\n  scope: security, availability, and confidentiality of customer data\n  period: June 1, 2024 - November 30, 2024\n  issuer: null\n  report_access: unstated\n  text: 'SOC 2 Type II Certification: June 1, 2024 - November 30, 2024'\n- framework: PCI-DSS\n  type: Level 1 Service Provider\n  scope:\
  \ null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: Checkout.com has successfully certified for PCI DSS as a Level 1 Service Provider in 2025!\n- framework: ISO27001\n  type: ISO 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: CyberEssentials\n  type: Cyber Essentials Plus\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Checkout.com has recertified for Cyber Essentials+\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/checkout/compliance/checkout-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Checkout's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Fintech
- E-Commerce
- Global
---
