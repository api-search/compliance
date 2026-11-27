---
api_specs:
- filename: nomic-ai-embeddings-api-openapi.yml
  format: yaml
  label: Nomic AI Embeddings API
  slug: nomic-ai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nomic-ai/openapi/nomic-ai-embeddings-api-openapi.yml
- filename: nomic-ai-files-api-openapi.yml
  format: yaml
  label: Nomic AI Files API
  slug: nomic-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nomic-ai/openapi/nomic-ai-files-api-openapi.yml
- filename: nomic-ai-tasks-api-openapi.yml
  format: yaml
  label: Nomic AI Tasks API
  slug: nomic-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nomic-ai/openapi/nomic-ai-tasks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Report 2025 Our Latest SOC 2 Type 2 Report Request
    type: SOC 2 Type 2 Report
  trust_center:
    url: https://security.nomic.ai/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nomic AI
provenance_date: '2026-11-10'
provider_name: Nomic AI
provider_slug: nomic-ai
slug: nomic-ai-compliance
source_date: '2026-11-10'
source_filename: nomic-ai-compliance.yml
source_heading: Compliance
source_page: https://security.nomic.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nomic AI\naid: nomic-ai\nurl: https://security.nomic.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/nomic-ai-trust-center.yml\ntrust_center:\n  url: https://security.nomic.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Report 2025 Our Latest SOC 2 Type 2 Report Request\n"
source_yaml_url: https://artifacts.apis.io/nomic-ai/compliance/nomic-ai-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Nomic AI's own page on 2026-11-10.
synthetic: false
tags:
- Embeddings
- Data Exploration
- LLM
- Open Source
- RAG
- Atlas
---
