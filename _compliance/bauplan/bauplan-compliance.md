---
api_specs:
- filename: bauplan-bauplanlabs-api-openapi.yml
  format: yaml
  label: Bauplan Bauplanlabs API
  slug: bauplan-bauplanlabs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bauplan/openapi/bauplan-bauplanlabs-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Request
    type: Type 2 report
  trust_center:
    url: https://security.bauplanlabs.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bauplan
provenance_date: '2026-11-09'
provider_name: Bauplan
provider_slug: bauplan
slug: bauplan-compliance
source_date: '2026-11-09'
source_filename: bauplan-compliance.yml
source_heading: Compliance
source_page: https://security.bauplanlabs.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bauplan\naid: bauplan\nurl: https://security.bauplanlabs.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://security.bauplanlabs.com/\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Request\n"
source_yaml_url: https://artifacts.apis.io/bauplan/compliance/bauplan-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Bauplan's own page on 2026-11-09.
synthetic: false
tags:
- Data Engineering
- AI Agents
- Serverless Platform
- Data Pipeline
- Data Integration
- Isolation and Rollback
---
