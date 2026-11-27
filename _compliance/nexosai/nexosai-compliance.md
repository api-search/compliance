---
api_specs:
- filename: nexosai-agent-management-api-openapi.yml
  format: yaml
  label: nexos.ai Agent Management API
  slug: nexosai-agent-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-agent-management-api-openapi.yml
- filename: nexosai-assistant-management-api-openapi.yml
  format: yaml
  label: nexos.ai Assistant Management API
  slug: nexosai-assistant-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-assistant-management-api-openapi.yml
- filename: nexosai-audio-api-openapi.yml
  format: yaml
  label: nexos.ai Audio API
  slug: nexosai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-audio-api-openapi.yml
- filename: nexosai-batches-api-openapi.yml
  format: yaml
  label: nexos.ai Batches API
  slug: nexosai-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-batches-api-openapi.yml
- filename: nexosai-budget-limit-management-api-openapi.yml
  format: yaml
  label: nexos.ai Budget Limit Management API
  slug: nexosai-budget-limit-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-budget-limit-management-api-openapi.yml
- filename: nexosai-company-management-api-openapi.yml
  format: yaml
  label: nexos.ai Company Management API
  slug: nexosai-company-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-company-management-api-openapi.yml
- filename: nexosai-embeddings-api-openapi.yml
  format: yaml
  label: nexos.ai Embeddings API
  slug: nexosai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-embeddings-api-openapi.yml
- filename: nexosai-files-api-openapi.yml
  format: yaml
  label: nexos.ai Files API
  slug: nexosai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-files-api-openapi.yml
- filename: nexosai-images-api-openapi.yml
  format: yaml
  label: nexos.ai Images API
  slug: nexosai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-images-api-openapi.yml
- filename: nexosai-messages-api-openapi.yml
  format: yaml
  label: nexos.ai Messages API
  slug: nexosai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-messages-api-openapi.yml
- filename: nexosai-models-api-openapi.yml
  format: yaml
  label: nexos.ai Models API
  slug: nexosai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-models-api-openapi.yml
- filename: nexosai-responses-api-openapi.yml
  format: yaml
  label: nexos.ai Responses API
  slug: nexosai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-responses-api-openapi.yml
- filename: nexosai-storage-api-openapi.yml
  format: yaml
  label: nexos.ai Storage API
  slug: nexosai-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-storage-api-openapi.yml
- filename: nexosai-team-management-api-openapi.yml
  format: yaml
  label: nexos.ai Team Management API
  slug: nexosai-team-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-team-management-api-openapi.yml
- filename: nexosai-user-management-api-openapi.yml
  format: yaml
  label: nexos.ai User Management API
  slug: nexosai-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-user-management-api-openapi.yml
- filename: nexosai-chat-completions-api-openapi.yml
  format: yaml
  label: nexos.ai Chat Completions API
  slug: nexosai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexosai/openapi/nexosai-chat-completions-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: have the ability to request access to detailed security and compliance documentation
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO/IEC 27001:2022
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 42001
    type: ISO/IEC 42001
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR
  trust_center:
    url: https://trust.nexos.ai/
frameworks:
- GDPR
- ISO27001
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: nexos.ai
provenance_date: '2026-11-10'
provider_name: nexos.ai
provider_slug: nexosai
slug: nexosai-compliance
source_date: '2026-11-10'
source_filename: nexosai-compliance.yml
source_heading: Compliance
source_page: https://trust.nexos.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: nexos.ai\naid: nexosai\nurl: https://trust.nexos.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.nexos.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: have the ability to request access to detailed security and compliance documentation\n- framework: ISO27001\n  type: ISO/IEC 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO42001\n  type: ISO/IEC 42001\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: ISO 42001\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/nexosai/compliance/nexosai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from nexos.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- AI Gateway
- Machine Learning
- Embeddings
- Agents
- Developer Tools
- OpenAI-Compatible
---
