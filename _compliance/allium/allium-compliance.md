---
api_specs:
- filename: allium-explorer-api-openapi.yml
  format: yaml
  label: Allium Explorer API
  slug: allium-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allium/openapi/allium-explorer-api-openapi.yml
- filename: allium-ping-api-openapi.yml
  format: yaml
  label: Allium Ping API
  slug: allium-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allium/openapi/allium-ping-api-openapi.yml
- filename: allium-polygon-api-openapi.yml
  format: yaml
  label: Allium Polygon API
  slug: allium-polygon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allium/openapi/allium-polygon-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: self-request and download Allium's security compliance certifications, reports and attestations
    type: Type 2
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 1
    type: Type 1
  - framework: SOC1
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 1 Type 2
    type: Type 2
  - framework: SOC1
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 1 Type 1
    type: Type 1
  trust_center:
    url: https://trust.allium.so/
frameworks:
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Allium
provenance_date: '2026-11-09'
provider_name: Allium
provider_slug: allium
slug: allium-compliance
source_date: '2026-11-09'
source_filename: allium-compliance.yml
source_heading: Compliance
source_page: https://trust.allium.so/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Allium\naid: allium\nurl: https://trust.allium.so/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.allium.so/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: self-request and download Allium's security compliance certifications, reports and attestations\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 1\n- framework: SOC1\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 1 Type\
  \ 2\n- framework: SOC1\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 1 Type 1\n"
source_yaml_url: https://artifacts.apis.io/allium/compliance/allium-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Allium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Analytics
- Blockchain
- Cryptocurrency
- Web3
- Data Infrastructure
- Real-Time Data
- Stablecoins
- DeFi
- Machine Payments
---
