---
api_specs:
- filename: squarespace-orders-api-openapi.yml
  format: yaml
  label: Squarespace Orders API
  slug: squarespace-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-orders-api-openapi.yml
- filename: squarespace-products-api-openapi.yml
  format: yaml
  label: Squarespace Products API
  slug: squarespace-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-products-api-openapi.yml
- filename: squarespace-inventory-api-openapi.yml
  format: yaml
  label: Squarespace Inventory API
  slug: squarespace-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-inventory-api-openapi.yml
- filename: squarespace-profiles-api-openapi.yml
  format: yaml
  label: Squarespace Profiles API
  slug: squarespace-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-profiles-api-openapi.yml
- filename: squarespace-transactions-api-openapi.yml
  format: yaml
  label: Squarespace Transactions API
  slug: squarespace-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-transactions-api-openapi.yml
- filename: squarespace-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Squarespace Webhook Subscriptions API
  slug: squarespace-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-webhook-subscriptions-api-openapi.yml
- filename: squarespace-site-api-openapi.yml
  format: yaml
  label: Squarespace Site API
  slug: squarespace-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-site-api-openapi.yml
- filename: squarespace-analytics-api-openapi.yml
  format: yaml
  label: Squarespace Analytics API
  slug: squarespace-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-analytics-api-openapi.yml
- filename: squarespace-contacts-api-openapi.yml
  format: yaml
  label: Squarespace Contacts API
  slug: squarespace-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-contacts-api-openapi.yml
- filename: squarespace-discounts-api-openapi.yml
  format: yaml
  label: Squarespace Discounts API
  slug: squarespace-discounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-discounts-api-openapi.yml
- filename: squarespace-websites-api-openapi.yml
  format: yaml
  label: Squarespace Websites API
  slug: squarespace-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/squarespace/openapi/squarespace-websites-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: built-in payment processor integrations
    text: All of Squarespace’s built-in payment processor integrations are compliant with PCI-DSS.
    type: compliance statement
  trust_center:
    url: https://www.squarespace.com/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Squarespace
provenance_date: '2026-11-10'
provider_name: Squarespace
provider_slug: squarespace
slug: squarespace-compliance
source_date: '2026-11-10'
source_filename: squarespace-compliance.yml
source_heading: Compliance
source_page: https://www.squarespace.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Squarespace\naid: squarespace\nurl: https://www.squarespace.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/squarespace-trust-center.yml\ntrust_center:\n  url: https://www.squarespace.com/security\nattestations:\n- framework: PCI-DSS\n  type: compliance statement\n  scope: built-in payment processor integrations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All of Squarespace’s built-in payment processor integrations are compliant with PCI-DSS.\n"
source_yaml_url: https://artifacts.apis.io/squarespace/compliance/squarespace-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Squarespace's own page on 2026-11-10.
synthetic: false
tags:
- Commerce
- E-Commerce
- Marketing
- Payments
- Retail
- Website Builder
- Webhook
---
