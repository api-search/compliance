---
api_specs:
- filename: ryft-ingest-api-openapi.yml
  format: yaml
  label: Ryft Ingest API
  slug: ryft-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ryft/openapi/ryft-ingest-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC2 (Type II) compliant
    type: Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO-27001 compliant
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant
    type: null
  trust_center:
    url: https://docs.ryft.io/administration/security-and-privacy
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ryft
provenance_date: '2026-11-10'
provider_name: Ryft
provider_slug: ryft
slug: ryft-compliance
source_date: '2026-11-10'
source_filename: ryft-compliance.yml
source_heading: Compliance
source_page: https://docs.ryft.io/administration/security-and-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ryft\naid: ryft\nurl: https://docs.ryft.io/administration/security-and-privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.ryft.io/administration/security-and-privacy\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC2 (Type II) compliant\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO-27001 compliant\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/ryft/compliance/ryft-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ryft's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Data Lake
- Lakehouse
- Apache Iceberg
- Data Management
- Analytics
- Query Optimization
- Artificial Intelligence
- MCP
---
