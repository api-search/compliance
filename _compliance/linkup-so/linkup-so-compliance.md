---
api_specs:
- filename: linkup-so-credits-api-openapi.yml
  format: yaml
  label: Linkup Credits API
  slug: linkup-so-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-credits-api-openapi.yml
- filename: linkup-so-fetch-api-openapi.yml
  format: yaml
  label: Linkup Fetch API
  slug: linkup-so-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-fetch-api-openapi.yml
- filename: linkup-so-research-api-openapi.yml
  format: yaml
  label: Linkup Research API
  slug: linkup-so-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-research-api-openapi.yml
- filename: linkup-so-search-api-openapi.yml
  format: yaml
  label: Linkup Search API
  slug: linkup-so-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-search-api-openapi.yml
- filename: linkup-so-extract-api-openapi.yml
  format: yaml
  label: Linkup Extract API
  slug: linkup-so-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-extract-api-openapi.yml
- filename: linkup-so-responses-api-openapi.yml
  format: yaml
  label: Linkup Responses API
  slug: linkup-so-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-responses-api-openapi.yml
- filename: linkup-so-rewind-api-openapi.yml
  format: yaml
  label: Linkup Rewind API
  slug: linkup-so-rewind-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-rewind-api-openapi.yml
- filename: linkup-so-tasks-api-openapi.yml
  format: yaml
  label: Linkup Tasks API
  slug: linkup-so-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/linkup-so/openapi/linkup-so-tasks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 type 2 report
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.linkup.so/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Linkup
provenance_date: '2026-11-09'
provider_name: Linkup
provider_slug: linkup-so
slug: linkup-so-compliance
source_date: '2026-11-09'
source_filename: linkup-so-compliance.yml
source_heading: Compliance
source_page: https://trust.linkup.so/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Linkup\naid: linkup-so\nurl: https://trust.linkup.so/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/linkup-so-trust-center.yml\ntrust_center:\n  url: https://trust.linkup.so/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 type 2 report\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/linkup-so/compliance/linkup-so-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Linkup's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Web Search
- Grounding
- RAG
---
