---
api_specs:
- filename: ordergroove-customers-api-openapi.yml
  format: yaml
  label: Ordergroove Customers API
  slug: ordergroove-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordergroove/openapi/ordergroove-customers-api-openapi.yml
- filename: ordergroove-items-api-openapi.yml
  format: yaml
  label: Ordergroove Items API
  slug: ordergroove-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordergroove/openapi/ordergroove-items-api-openapi.yml
- filename: ordergroove-offers-api-openapi.yml
  format: yaml
  label: Ordergroove Offers API
  slug: ordergroove-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordergroove/openapi/ordergroove-offers-api-openapi.yml
- filename: ordergroove-orders-api-openapi.yml
  format: yaml
  label: Ordergroove Orders API
  slug: ordergroove-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordergroove/openapi/ordergroove-orders-api-openapi.yml
- filename: ordergroove-products-api-openapi.yml
  format: yaml
  label: Ordergroove Products API
  slug: ordergroove-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordergroove/openapi/ordergroove-products-api-openapi.yml
- filename: ordergroove-subscriptions-api-openapi.yml
  format: yaml
  label: Ordergroove Subscriptions API
  slug: ordergroove-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordergroove/openapi/ordergroove-subscriptions-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: third party security assessor
    period: null
    report_access: on_request
    scope: Ordergroove services
    text: Ordergroove holds a Level 1 compliance with the Payment Card Industry Data Security Standards (PCI DSS)
    type: Level 1 compliance with PCI DSS
  - framework: SOC2
    issuer: Google Cloud Platform
    period: null
    report_access: on_request
    scope: Services hosted on Google Cloud Platform
    text: Ordergroove can provide a SOC 2 Type II report from our cloud provider upon request.
    type: SOC 2 Type II report from cloud provider
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Ordergroove
    text: Ordergroove is GDPR Compliant.
    type: Stated compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Ordergroove
    text: Ordergroove is CCPA Compliant.
    type: Stated compliance
  trust_center:
    url: https://www.ordergroove.com/security/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ordergroove
provenance_date: '2026-11-10'
provider_name: Ordergroove
provider_slug: ordergroove
slug: ordergroove-compliance
source_date: '2026-11-10'
source_filename: ordergroove-compliance.yml
source_heading: Compliance
source_page: https://www.ordergroove.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ordergroove\naid: ordergroove\nurl: https://www.ordergroove.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ordergroove-trust-center.yml\ntrust_center:\n  url: https://www.ordergroove.com/security/\nattestations:\n- framework: PCI-DSS\n  type: Level 1 compliance with PCI DSS\n  scope: Ordergroove services\n  period: null\n  issuer: third party security assessor\n  report_access: on_request\n  text: Ordergroove holds a Level 1 compliance with the Payment Card Industry Data Security Standards (PCI DSS)\n- framework: SOC2\n  type: SOC 2 Type II report from cloud provider\n  scope: Services\
  \ hosted on Google Cloud Platform\n  period: null\n  issuer: Google Cloud Platform\n  report_access: on_request\n  text: Ordergroove can provide a SOC 2 Type II report from our cloud provider upon request.\n- framework: GDPR\n  type: Stated compliance\n  scope: Ordergroove\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ordergroove is GDPR Compliant.\n- framework: CCPA\n  type: Stated compliance\n  scope: Ordergroove\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ordergroove is CCPA Compliant.\n"
source_yaml_url: https://artifacts.apis.io/ordergroove/compliance/ordergroove-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Ordergroove's own page on 2026-11-10.
synthetic: false
tags:
- Subscription
- Recurring Commerce
- Relationship Commerce
- E-Commerce
- Autoship
- Direct to Consumer
- Retail
- Subscription Management
---
