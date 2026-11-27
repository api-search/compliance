---
api_specs:
- filename: orderful-conversion-api-openapi.yml
  format: yaml
  label: Orderful Conversion API
  slug: orderful-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-conversion-api-openapi.yml
- filename: orderful-delivery-api-openapi.yml
  format: yaml
  label: Orderful Delivery API
  slug: orderful-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-delivery-api-openapi.yml
- filename: orderful-inbox-api-openapi.yml
  format: yaml
  label: Orderful Inbox API
  slug: orderful-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-inbox-api-openapi.yml
- filename: orderful-label-api-openapi.yml
  format: yaml
  label: Orderful Label API
  slug: orderful-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-label-api-openapi.yml
- filename: orderful-organization-api-openapi.yml
  format: yaml
  label: Orderful Organization API
  slug: orderful-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-organization-api-openapi.yml
- filename: orderful-poller-api-openapi.yml
  format: yaml
  label: Orderful Poller API
  slug: orderful-poller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-poller-api-openapi.yml
- filename: orderful-relationship-api-openapi.yml
  format: yaml
  label: Orderful Relationship API
  slug: orderful-relationship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-relationship-api-openapi.yml
- filename: orderful-transaction-api-openapi.yml
  format: yaml
  label: Orderful Transaction API
  slug: orderful-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-transaction-api-openapi.yml
- filename: orderful-transaction-v3-api-openapi.yml
  format: yaml
  label: Orderful Transaction (v3) API
  slug: orderful-transaction-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-transaction-v3-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type 2 Audit Report
    type: Type 2 Audit Report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Audit Report
    type: Type 2 Audit Report
  trust_center:
    url: https://trust.orderful.com/
frameworks:
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Orderful
provenance_date: '2026-11-10'
provider_name: Orderful
provider_slug: orderful
slug: orderful-compliance
source_date: '2026-11-10'
source_filename: orderful-compliance.yml
source_heading: Compliance
source_page: https://trust.orderful.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Orderful\naid: orderful\nurl: https://trust.orderful.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/orderful-trust-center.yml\ntrust_center:\n  url: https://trust.orderful.com/\nattestations:\n- framework: SOC1\n  type: Type 2 Audit Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2 Audit Report\n- framework: SOC2\n  type: Type 2 Audit Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Audit Report\n"
source_yaml_url: https://artifacts.apis.io/orderful/compliance/orderful-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Orderful's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EDI
- Electronic Data Interchange
- Supply Chain
- B2B
- Logistics
- Retail
- Transaction
- Integration
---
