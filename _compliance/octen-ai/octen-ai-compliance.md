---
api_specs:
- filename: octen-ai-answer-api-openapi.yml
  format: yaml
  label: Octen Answer API
  slug: octen-ai-answer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-answer-api-openapi.yml
- filename: octen-ai-broad-search-api-openapi.yml
  format: yaml
  label: Octen Broad Search API
  slug: octen-ai-broad-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-broad-search-api-openapi.yml
- filename: octen-ai-business-search-api-openapi.yml
  format: yaml
  label: Octen Business Search API
  slug: octen-ai-business-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-business-search-api-openapi.yml
- filename: octen-ai-embedding-api-openapi.yml
  format: yaml
  label: Octen Embedding API
  slug: octen-ai-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-embedding-api-openapi.yml
- filename: octen-ai-extract-api-openapi.yml
  format: yaml
  label: Octen Extract API
  slug: octen-ai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-extract-api-openapi.yml
- filename: octen-ai-grounded-generation-api-openapi.yml
  format: yaml
  label: Octen Grounded Generation API
  slug: octen-ai-grounded-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-grounded-generation-api-openapi.yml
- filename: octen-ai-image-search-api-openapi.yml
  format: yaml
  label: Octen Image Search API
  slug: octen-ai-image-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-image-search-api-openapi.yml
- filename: octen-ai-images-api-openapi.yml
  format: yaml
  label: Octen Images API
  slug: octen-ai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-images-api-openapi.yml
- filename: octen-ai-messages-api-openapi.yml
  format: yaml
  label: Octen Messages API
  slug: octen-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-messages-api-openapi.yml
- filename: octen-ai-news-search-api-openapi.yml
  format: yaml
  label: Octen News Search API
  slug: octen-ai-news-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-news-search-api-openapi.yml
- filename: octen-ai-research-api-openapi.yml
  format: yaml
  label: Octen Research API
  slug: octen-ai-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-research-api-openapi.yml
- filename: octen-ai-search-api-openapi.yml
  format: yaml
  label: Octen Search API
  slug: octen-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-search-api-openapi.yml
- filename: octen-ai-video-search-api-openapi.yml
  format: yaml
  label: Octen Video Search API
  slug: octen-ai-video-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-video-search-api-openapi.yml
- filename: octen-ai-videos-api-openapi.yml
  format: yaml
  label: Octen Videos API
  slug: octen-ai-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-videos-api-openapi.yml
- filename: octen-ai-vl-embedding-api-openapi.yml
  format: yaml
  label: Octen Vl Embedding API
  slug: octen-ai-vl-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-vl-embedding-api-openapi.yml
- filename: octen-ai-chat-completions-api-openapi.yml
  format: yaml
  label: Octen Chat Completions API
  slug: octen-ai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octen-ai/openapi/octen-ai-chat-completions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II Certified
    type: SOC 2 Type II Certified
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://docs.octen.ai/resources/security-&-compliance.md
    text: SOC 2 Type II | Certified
    type: Type II
  trust_center:
    url: https://docs.octen.ai/resources/security-&-compliance
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Octen
provenance_date: '2026-11-10'
provider_name: Octen
provider_slug: octen-ai
slug: octen-ai-compliance
source_date: '2026-11-10'
source_filename: octen-ai-compliance.yml
source_heading: Compliance
source_page: https://docs.octen.ai/resources/security-&-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Octen\naid: octen-ai\nurl: https://docs.octen.ai/resources/security-&-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/octen-ai-trust-center.yml\n  sources:\n  - https://docs.octen.ai/resources/security-&-compliance\n  - https://docs.octen.ai/resources/security-&-compliance.md\ntrust_center:\n  url: https://docs.octen.ai/resources/security-&-compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II Certified\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Certified\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II | Certified\n  source: https://docs.octen.ai/resources/security-&-compliance.md\n"
source_yaml_url: https://artifacts.apis.io/octen-ai/compliance/octen-ai-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Octen's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Web Search
- Artificial Intelligence
- LLM
- Embeddings
- Content Extraction
- Model Gateway
- MCP
- Agents
- Deep Research
- Company
---
