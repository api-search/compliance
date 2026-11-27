---
api_specs:
- filename: veho-labels-api-openapi.yml
  format: yaml
  label: Veho Labels API
  slug: veho-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-labels-api-openapi.yml
- filename: veho-manifests-api-openapi.yml
  format: yaml
  label: Veho Manifests API
  slug: veho-manifests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-manifests-api-openapi.yml
- filename: veho-merchants-api-openapi.yml
  format: yaml
  label: Veho Merchants API
  slug: veho-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-merchants-api-openapi.yml
- filename: veho-orders-api-openapi.yml
  format: yaml
  label: Veho Orders API
  slug: veho-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-orders-api-openapi.yml
- filename: veho-packages-api-openapi.yml
  format: yaml
  label: Veho Packages API
  slug: veho-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-packages-api-openapi.yml
- filename: veho-quotes-api-openapi.yml
  format: yaml
  label: Veho Quotes API
  slug: veho-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-quotes-api-openapi.yml
- filename: veho-webhooks-api-openapi.yml
  format: yaml
  label: Veho Webhooks API
  slug: veho-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-webhooks-api-openapi.yml
- filename: veho-zips-api-openapi.yml
  format: yaml
  label: Veho Zips API
  slug: veho-zips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veho/openapi/veho-zips-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: Schellman (ANAB and UKAS accredited auditing firm)
    period: null
    report_access: unstated
    scope: Information security management system supporting the parcel delivery platform, including Consumer and Driver mobile applications and package tracking website
    text: Veho has been certified to the ISO/IEC 27001 standard for the information security management system supporting our parcel delivery platform
    type: ISO/IEC 27001 certification
  trust_center:
    url: https://www.shipveho.com/security
frameworks:
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Veho
provenance_date: '2026-11-10'
provider_name: Veho
provider_slug: veho
slug: veho-compliance
source_date: '2026-11-10'
source_filename: veho-compliance.yml
source_heading: Compliance
source_page: https://www.shipveho.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Veho\naid: veho\nurl: https://www.shipveho.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.shipveho.com/security\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: Information security management system supporting the parcel delivery platform, including Consumer and\n    Driver mobile applications and package tracking website\n  period: null\n  issuer: Schellman (ANAB and UKAS accredited auditing firm)\n  report_access: unstated\n  text: Veho has been certified to the ISO/IEC 27001 standard for the information security management system supporting\n\
  \    our parcel delivery platform\n"
source_yaml_url: https://artifacts.apis.io/veho/compliance/veho-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Veho's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Last Mile Delivery
- Package Tracking
- E-Commerce
- Webhook
- Delivery
---
