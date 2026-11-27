---
api_specs:
- filename: popsql-data-catalog-api-openapi.yml
  format: yaml
  label: PopSQL Data Catalog API
  slug: popsql-data-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popsql/openapi/popsql-data-catalog-api-openapi.yml
- filename: popsql-query-runs-api-openapi.yml
  format: yaml
  label: PopSQL Query Runs API
  slug: popsql-query-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/popsql/openapi/popsql-query-runs-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PopSQL is SOC 2 Type II compliant.
    type: Type II
  trust_center:
    url: https://popsql.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PopSQL
provenance_date: '2026-11-10'
provider_name: PopSQL
provider_slug: popsql
slug: popsql-compliance
source_date: '2026-11-10'
source_filename: popsql-compliance.yml
source_heading: Compliance
source_page: https://popsql.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PopSQL\naid: popsql\nurl: https://popsql.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://popsql.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PopSQL is SOC 2 Type II compliant.\n"
source_yaml_url: https://artifacts.apis.io/popsql/compliance/popsql-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from PopSQL's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SQL
- Collaboration
- Data Analytics
- Cloud
---
