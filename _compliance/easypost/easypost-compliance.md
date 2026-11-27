---
api_specs:
- filename: easypost-webhooks-asyncapi.yml
  format: yaml
  label: EasyPost Webhooks API
  slug: webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/easypost/asyncapi/easypost-webhooks-asyncapi.yml
- filename: easypost-addresses-api-openapi.yml
  format: yaml
  label: EasyPost Addresses API
  slug: easypost-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easypost/openapi/easypost-addresses-api-openapi.yml
- filename: easypost-parcels-api-openapi.yml
  format: yaml
  label: EasyPost Parcels API
  slug: easypost-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easypost/openapi/easypost-parcels-api-openapi.yml
- filename: easypost-refunds-api-openapi.yml
  format: yaml
  label: EasyPost Refunds API
  slug: easypost-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easypost/openapi/easypost-refunds-api-openapi.yml
- filename: easypost-reports-api-openapi.yml
  format: yaml
  label: EasyPost Reports API
  slug: easypost-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easypost/openapi/easypost-reports-api-openapi.yml
- filename: easypost-shipments-api-openapi.yml
  format: yaml
  label: EasyPost Shipments API
  slug: easypost-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easypost/openapi/easypost-shipments-api-openapi.yml
- filename: easypost-trackers-api-openapi.yml
  format: yaml
  label: EasyPost Trackers API
  slug: easypost-trackers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easypost/openapi/easypost-trackers-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: BARR Advisory, P.A.
    period: July 1, 2025 through June 30, 2026
    report_access: unstated
    scope: EasyPost and EasyPost Analytics
    text: Please note that both reports covers the period from July 1, 2025 through June 30, 2026.
    type: SOC 2 Type 2 report
  trust_center:
    url: https://trust.easypost.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: EasyPost
provenance_date: '2026-11-09'
provider_name: EasyPost
provider_slug: easypost
slug: easypost-compliance
source_date: '2026-11-09'
source_filename: easypost-compliance.yml
source_heading: Compliance
source_page: https://trust.easypost.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: EasyPost\naid: easypost\nurl: https://trust.easypost.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/easypost-trust-center.yml\ntrust_center:\n  url: https://trust.easypost.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: EasyPost and EasyPost Analytics\n  period: July 1, 2025 through June 30, 2026\n  issuer: BARR Advisory, P.A.\n  report_access: unstated\n  text: Please note that both reports covers the period from July 1, 2025 through June 30, 2026.\n"
source_yaml_url: https://artifacts.apis.io/easypost/compliance/easypost-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from EasyPost's own page on 2026-11-09.
synthetic: false
tags:
- Shipping
- Logistics
- Multi-Carrier
- Tracking
- Labels
- Insurance
---
