---
api_specs:
- filename: mendable-chat-api-openapi.yml
  format: yaml
  label: Mendable Chat API
  slug: mendable-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendable/openapi/mendable-chat-api-openapi.yml
- filename: mendable-conversations-api-openapi.yml
  format: yaml
  label: Mendable Conversations API
  slug: mendable-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendable/openapi/mendable-conversations-api-openapi.yml
- filename: mendable-ingestion-api-openapi.yml
  format: yaml
  label: Mendable Ingestion API
  slug: mendable-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendable/openapi/mendable-ingestion-api-openapi.yml
- filename: mendable-ratings-api-openapi.yml
  format: yaml
  label: Mendable Ratings API
  slug: mendable-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendable/openapi/mendable-ratings-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Mendable is SOC 2 Type II compliant.
    type: SOC 2 Type II
  trust_center:
    url: https://www.mendable.ai/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mendable
provenance_date: '2026-11-10'
provider_name: Mendable
provider_slug: mendable
slug: mendable-compliance
source_date: '2026-11-10'
source_filename: mendable-compliance.yml
source_heading: Compliance
source_page: https://www.mendable.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mendable\naid: mendable\nurl: https://www.mendable.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mendable-trust-center.yml\ntrust_center:\n  url: https://www.mendable.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mendable is SOC 2 Type II compliant.\n"
source_yaml_url: https://artifacts.apis.io/mendable/compliance/mendable-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Mendable's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Answers
- Enterprise Search
- RAG
- Support
---
