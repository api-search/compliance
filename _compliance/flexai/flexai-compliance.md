---
api_specs:
- filename: flexai-completions-api-openapi.yml
  format: yaml
  label: FlexAI Completions API
  slug: flexai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-completions-api-openapi.yml
- filename: flexai-embeddings-api-openapi.yml
  format: yaml
  label: FlexAI Embeddings API
  slug: flexai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-embeddings-api-openapi.yml
- filename: flexai-models-api-openapi.yml
  format: yaml
  label: FlexAI Models API
  slug: flexai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-models-api-openapi.yml
- filename: flexai-usage-api-openapi.yml
  format: yaml
  label: FlexAI Usage API
  slug: flexai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-usage-api-openapi.yml
- filename: flexai-chat-completions-api-openapi.yml
  format: yaml
  label: FlexAI Chat Completions API
  slug: flexai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-chat-completions-api-openapi.yml
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
    type: SOC2 type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://security.flex.ai
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: FlexAI
provenance_date: '2026-11-09'
provider_name: FlexAI
provider_slug: flexai
slug: flexai-compliance
source_date: '2026-11-09'
source_filename: flexai-compliance.yml
source_heading: Compliance
source_page: https://security.flex.ai
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: FlexAI\naid: flexai\nurl: https://security.flex.ai\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://security.flex.ai\nattestations:\n- framework: SOC2\n  type: SOC2 type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 type 2 report\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/flexai/compliance/flexai-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from FlexAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- LLM
- OpenAI-Compatible
- GPU Compute
- Embeddings
- Fine-Tuning
- Agents
---
