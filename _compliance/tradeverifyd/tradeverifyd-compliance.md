---
api_specs:
- filename: tradeverifyd-documents-api-openapi.yml
  format: yaml
  label: Tradeverifyd Documents API
  slug: tradeverifyd-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-documents-api-openapi.yml
- filename: tradeverifyd-entity-api-openapi.yml
  format: yaml
  label: Tradeverifyd Entity API
  slug: tradeverifyd-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-entity-api-openapi.yml
- filename: tradeverifyd-flags-api-openapi.yml
  format: yaml
  label: Tradeverifyd Flags API
  slug: tradeverifyd-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-flags-api-openapi.yml
- filename: tradeverifyd-organizations-api-openapi.yml
  format: yaml
  label: Tradeverifyd Organizations API
  slug: tradeverifyd-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-organizations-api-openapi.yml
- filename: tradeverifyd-relationships-api-openapi.yml
  format: yaml
  label: Tradeverifyd Relationships API
  slug: tradeverifyd-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-relationships-api-openapi.yml
- filename: tradeverifyd-reports-api-openapi.yml
  format: yaml
  label: Tradeverifyd Reports API
  slug: tradeverifyd-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-reports-api-openapi.yml
- filename: tradeverifyd-risk-events-api-openapi.yml
  format: yaml
  label: Tradeverifyd Risk Events API
  slug: tradeverifyd-risk-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-risk-events-api-openapi.yml
- filename: tradeverifyd-scitt-reference-apis-api-openapi.yml
  format: yaml
  label: Tradeverifyd SCITT Reference APIs API
  slug: tradeverifyd-scitt-reference-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-scitt-reference-apis-api-openapi.yml
- filename: tradeverifyd-shipments-api-openapi.yml
  format: yaml
  label: Tradeverifyd Shipments API
  slug: tradeverifyd-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-shipments-api-openapi.yml
- filename: tradeverifyd-system-api-openapi.yml
  format: yaml
  label: Tradeverifyd System API
  slug: tradeverifyd-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-system-api-openapi.yml
- filename: tradeverifyd-transparency-log-api-openapi.yml
  format: yaml
  label: Tradeverifyd Transparency Log API
  slug: tradeverifyd-transparency-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-transparency-log-api-openapi.yml
- filename: tradeverifyd-us-customs-api-openapi.yml
  format: yaml
  label: Tradeverifyd US Customs API
  slug: tradeverifyd-us-customs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-us-customs-api-openapi.yml
- filename: tradeverifyd-verifiable-credentials-api-openapi.yml
  format: yaml
  label: Tradeverifyd Verifiable Credentials API
  slug: tradeverifyd-verifiable-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradeverifyd/openapi/tradeverifyd-verifiable-credentials-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Controls
    type: controls listing
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Microsoft Supplier Security & Privacy Assurance Program
    type: supplier assurance program
  trust_center:
    url: https://trust.tradeverifyd.com/
frameworks:
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tradeverifyd
provenance_date: '2026-11-10'
provider_name: Tradeverifyd
provider_slug: tradeverifyd
slug: tradeverifyd-compliance
source_date: '2026-11-10'
source_filename: tradeverifyd-compliance.yml
source_heading: Compliance
source_page: https://trust.tradeverifyd.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tradeverifyd\naid: tradeverifyd\nurl: https://trust.tradeverifyd.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tradeverifyd-trust-center.yml\ntrust_center:\n  url: https://trust.tradeverifyd.com/\nattestations:\n- framework: ISO27001\n  type: controls listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Controls\n- framework: other\n  type: supplier assurance program\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Microsoft Supplier Security & Privacy Assurance Program\n"
source_yaml_url: https://artifacts.apis.io/tradeverifyd/compliance/tradeverifyd-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Tradeverifyd's own page on 2026-11-10.
synthetic: false
tags:
- Supply Chain
- Trade Compliance
- Risk Management
- Verifiable Credentials
- Customs
- Entity Resolution
- Logistics
---
