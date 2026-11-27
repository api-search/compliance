---
api_specs:
- filename: hyperpay-copyandpay-api-openapi.yml
  format: yaml
  label: HyperPay COPYandPAY API
  slug: hyperpay-copyandpay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperpay/openapi/hyperpay-copyandpay-api-openapi.yml
- filename: hyperpay-payments-api-openapi.yml
  format: yaml
  label: HyperPay Payments API
  slug: hyperpay-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperpay/openapi/hyperpay-payments-api-openapi.yml
- filename: hyperpay-query-api-openapi.yml
  format: yaml
  label: HyperPay Query API
  slug: hyperpay-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperpay/openapi/hyperpay-query-api-openapi.yml
- filename: hyperpay-registrations-api-openapi.yml
  format: yaml
  label: HyperPay Registrations API
  slug: hyperpay-registrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperpay/openapi/hyperpay-registrations-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: payment gateway
    text: HyperPay’s payment gateway is PCI-DSS compliant, ensuring world-class security standards, integrations and products on a fully certified platform.
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We have implemented world-class cybersecurity controls that are backed by industry leading certifications such as PCI DSS, ISO 27001, and ISO 27701.
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We have implemented world-class cybersecurity controls that are backed by industry leading certifications such as PCI DSS, ISO 27001, and ISO 27701.
    type: certification
  trust_center:
    url: https://www.hyperpay.com/
frameworks:
- ISO27001
- ISO27701
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: HyperPay
provenance_date: '2026-11-09'
provider_name: HyperPay
provider_slug: hyperpay
slug: hyperpay-compliance
source_date: '2026-11-09'
source_filename: hyperpay-compliance.yml
source_heading: Compliance
source_page: https://www.hyperpay.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: HyperPay\naid: hyperpay\nurl: https://www.hyperpay.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/hyperpay-trust-center.yml\ntrust_center:\n  url: https://www.hyperpay.com/\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: payment gateway\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HyperPay’s payment gateway is PCI-DSS compliant, ensuring world-class security standards, integrations and\n    products on a fully certified platform.\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: We have implemented world-class cybersecurity controls that are backed by industry leading certifications\n    such as PCI DSS, ISO 27001, and ISO 27701.\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have implemented world-class cybersecurity controls that are backed by industry leading certifications\n    such as PCI DSS, ISO 27001, and ISO 27701.\n"
source_yaml_url: https://artifacts.apis.io/hyperpay/compliance/hyperpay-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from HyperPay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- MENA
- Saudi Arabia
- mada
- Apple Pay
- Cards
---
