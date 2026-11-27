---
api_specs:
- filename: materialize-asyncapi.yml
  format: yaml
  label: Materialize Streaming Sources and Sinks (AsyncAPI)
  slug: materialize-streaming-asyncapi
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/materialize/asyncapi/materialize-asyncapi.yml
- filename: materialize-sql-api-openapi.yml
  format: yaml
  label: Materialize Sql API
  slug: materialize-sql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/materialize/openapi/materialize-sql-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Materialize Cloud
    text: Materialize Cloud is fully-managed and SOC 2 Type II certified, so you can meet compliance requirements without managing infrastructure.
    type: SOC 2 Type II certification
  trust_center:
    url: https://materialize.com/product/security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Materialize
provenance_date: '2026-11-10'
provider_name: Materialize
provider_slug: materialize
slug: materialize-compliance
source_date: '2026-11-10'
source_filename: materialize-compliance.yml
source_heading: Compliance
source_page: https://materialize.com/product/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Materialize\naid: materialize\nurl: https://materialize.com/product/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/materialize-trust-center.yml\ntrust_center:\n  url: https://materialize.com/product/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: Materialize Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Materialize Cloud is fully-managed and SOC 2 Type II certified, so you can meet compliance requirements\n    without managing infrastructure.\n"
source_yaml_url: https://artifacts.apis.io/materialize/compliance/materialize-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Materialize's own page on 2026-11-10.
synthetic: false
tags:
- Streaming
- Data Warehouse
- SQL
- Real-Time
- PostgreSQL Compatible
---
