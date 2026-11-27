---
api_specs:
- filename: datarails-health-api-openapi.yml
  format: yaml
  label: Datarails Health API
  slug: datarails-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-health-api-openapi.yml
- filename: datarails-ready-api-openapi.yml
  format: yaml
  label: Datarails Ready API
  slug: datarails-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-ready-api-openapi.yml
- filename: datarails-well-known-api-openapi.yml
  format: yaml
  label: Datarails .well Known API
  slug: datarails-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-well-known-api-openapi.yml
- filename: datarails-oauth-api-openapi.yml
  format: yaml
  label: Datarails OAUTH API
  slug: datarails-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-oauth-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: Datarails SOC 1 Type II 2026 Report
    type: Type II report
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: Datarails SOC 2 Type II 2026 Report
    type: Type II report
  trust_center:
    url: https://trust.datarails.com/overview
frameworks:
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Datarails
provenance_date: '2026-11-09'
provider_name: Datarails
provider_slug: datarails
slug: datarails-compliance
source_date: '2026-11-09'
source_filename: datarails-compliance.yml
source_heading: Compliance
source_page: https://trust.datarails.com/overview
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Datarails\naid: datarails\nurl: https://trust.datarails.com/overview\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.datarails.com/overview\nattestations:\n- framework: SOC1\n  type: Type II report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: Datarails SOC 1 Type II 2026 Report\n- framework: SOC2\n  type: Type II report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: Datarails SOC 2 Type II 2026 Report\n"
source_yaml_url: https://artifacts.apis.io/datarails/compliance/datarails-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Datarails's own page on 2026-11-09.
synthetic: false
tags:
- Company
- FP&A
- Financial Planning
- Finance
- Accounting
- Budgeting
- Forecasting
- Business Intelligence
- Reporting
- Data Integration
- MCP
- Artificial Intelligence
- Excel
- Software-as-a-Service
---
