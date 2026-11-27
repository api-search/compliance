---
api_specs:
- filename: memories-serve-api-openapi.yml
  format: yaml
  label: Memories Serve API
  slug: memories-serve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memories/openapi/memories-serve-api-openapi.yml
- filename: memories-stream-understanding-api-openapi.yml
  format: yaml
  label: Memories Stream Understanding API
  slug: memories-stream-understanding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memories/openapi/memories-stream-understanding-api-openapi.yml
- filename: memories-understand-api-openapi.yml
  format: yaml
  label: Memories Understand API
  slug: memories-understand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memories/openapi/memories-understand-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: across every deployment
    text: Memories.ai is SOC 2 certified, with encryption in transit and at rest, role-based access control, SSO, and complete audit trails across every deployment.
    type: SOC 2 certified
  trust_center:
    url: https://memories.ai/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Memories
provenance_date: '2026-11-10'
provider_name: Memories
provider_slug: memories
slug: memories-compliance
source_date: '2026-11-10'
source_filename: memories-compliance.yml
source_heading: Compliance
source_page: https://memories.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Memories\naid: memories\nurl: https://memories.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://memories.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 certified\n  scope: across every deployment\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Memories.ai is SOC 2 certified, with encryption in transit and at rest, role-based access control, SSO,\n    and complete audit trails across every deployment.\n"
source_yaml_url: https://artifacts.apis.io/memories/compliance/memories-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Memories's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video Intelligence
- Video Understanding
- Video Search
- Transcription
- Embeddings
- Multimodal AI
- Content Moderation
- AI Agents
- Machine Learning
---
