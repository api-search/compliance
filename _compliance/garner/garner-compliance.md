---
api_specs:
- filename: garner-facilities-api-openapi.yml
  format: yaml
  label: Garner Facilities API
  slug: garner-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-facilities-api-openapi.yml
- filename: garner-professionals-api-openapi.yml
  format: yaml
  label: Garner Professionals API
  slug: garner-professionals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-professionals-api-openapi.yml
- filename: garner-provider-annotations-api-openapi.yml
  format: yaml
  label: Garner Provider Annotations API
  slug: garner-provider-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-provider-annotations-api-openapi.yml
- filename: garner-providers-api-openapi.yml
  format: yaml
  label: Garner Providers API
  slug: garner-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-providers-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: system designed to keep clients' sensitive data secure
    text: Garner's SOC 2 Report is available upon request and under NDA.
    type: Type II audit
  trust_center:
    url: https://garnerhealth.com/news/garner-completes-soc-2-type-ii-certification
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Garner
provenance_date: '2026-11-09'
provider_name: Garner
provider_slug: garner
slug: garner-compliance
source_date: '2026-11-09'
source_filename: garner-compliance.yml
source_heading: Compliance
source_page: https://garnerhealth.com/news/garner-completes-soc-2-type-ii-certification
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Garner\naid: garner\nurl: https://garnerhealth.com/news/garner-completes-soc-2-type-ii-certification\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://garnerhealth.com/news/garner-completes-soc-2-type-ii-certification\nattestations:\n- framework: SOC2\n  type: Type II audit\n  scope: system designed to keep clients' sensitive data secure\n  period: null\n  issuer: null\n  report_access: nda\n  text: Garner's SOC 2 Report is available upon request and under NDA.\n"
source_yaml_url: https://artifacts.apis.io/garner/compliance/garner-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Garner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Healthcare
- Provider Data
- Care Navigation
- Health Insurance
- Claims Analytics
- Provider Search
- Doctor Quality
---
