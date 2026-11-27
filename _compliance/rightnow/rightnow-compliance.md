---
api_specs:
- filename: rightnow-audio-api-openapi.yml
  format: yaml
  label: RightNow AI Audio API
  slug: rightnow-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-audio-api-openapi.yml
- filename: rightnow-embeddings-api-openapi.yml
  format: yaml
  label: RightNow AI Embeddings API
  slug: rightnow-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-embeddings-api-openapi.yml
- filename: rightnow-images-api-openapi.yml
  format: yaml
  label: RightNow AI Images API
  slug: rightnow-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-images-api-openapi.yml
- filename: rightnow-models-api-openapi.yml
  format: yaml
  label: RightNow AI Models API
  slug: rightnow-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-models-api-openapi.yml
- filename: rightnow-rerank-api-openapi.yml
  format: yaml
  label: RightNow AI Rerank API
  slug: rightnow-rerank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-rerank-api-openapi.yml
- filename: rightnow-responses-api-openapi.yml
  format: yaml
  label: RightNow AI Responses API
  slug: rightnow-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-responses-api-openapi.yml
- filename: rightnow-chat-completions-api-openapi.yml
  format: yaml
  label: RightNow AI Chat Completions API
  slug: rightnow-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-chat-completions-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor under AICPA standards (auditor not named)
    period: null
    report_access: nda
    scope: security, availability, and confidentiality controls over platform components RunInfra operates directly
    text: RunInfra is SOC 2 Type II attested.
    type: SOC 2 Type II attestation
  trust_center:
    url: https://runinfra.ai/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: RightNow AI
provenance_date: '2026-11-10'
provider_name: RightNow AI
provider_slug: rightnow
slug: rightnow-compliance
source_date: '2026-11-10'
source_filename: rightnow-compliance.yml
source_heading: Compliance
source_page: https://runinfra.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: RightNow AI\naid: rightnow\nurl: https://runinfra.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/rightnow-trust-center.yml\ntrust_center:\n  url: https://runinfra.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation\n  scope: security, availability, and confidentiality controls over platform components RunInfra operates directly\n  period: null\n  issuer: independent auditor under AICPA standards (auditor not named)\n  report_access: nda\n  text: RunInfra is SOC 2 Type II attested.\n"
source_yaml_url: https://artifacts.apis.io/rightnow/compliance/rightnow-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from RightNow AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- GPU
- Model Deployment
- Serverless
- OpenAI-Compatible
- Embeddings
- MLOps
---
