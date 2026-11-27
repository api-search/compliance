---
api_specs:
- filename: parallel-ai-chat-api-beta-api-openapi.yml
  format: yaml
  label: Parallel Chat API (Beta) API
  slug: parallel-ai-chat-api-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-chat-api-beta-api-openapi.yml
- filename: parallel-ai-extract-api-openapi.yml
  format: yaml
  label: Parallel Extract API
  slug: parallel-ai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-extract-api-openapi.yml
- filename: parallel-ai-findall-api-openapi.yml
  format: yaml
  label: Parallel Find All API
  slug: parallel-ai-findall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-findall-api-openapi.yml
- filename: parallel-ai-memory-api-openapi.yml
  format: yaml
  label: Parallel Memory API
  slug: parallel-ai-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-memory-api-openapi.yml
- filename: parallel-ai-monitor-api-openapi.yml
  format: yaml
  label: Parallel Monitor API
  slug: parallel-ai-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-monitor-api-openapi.yml
- filename: parallel-ai-responses-api-api-openapi.yml
  format: yaml
  label: Parallel Responses API
  slug: parallel-ai-responses-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-responses-api-api-openapi.yml
- filename: parallel-ai-search-api-openapi.yml
  format: yaml
  label: Parallel Search API
  slug: parallel-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-search-api-openapi.yml
- filename: parallel-ai-decisions-api-openapi.yml
  format: yaml
  label: Parallel Decisions API
  slug: parallel-ai-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-decisions-api-openapi.yml
- filename: parallel-ai-apps-api-openapi.yml
  format: yaml
  label: Parallel Apps API
  slug: parallel-ai-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-apps-api-openapi.yml
- filename: parallel-ai-balance-api-openapi.yml
  format: yaml
  label: Parallel Balance API
  slug: parallel-ai-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-balance-api-openapi.yml
- filename: parallel-ai-image-search-api-openapi.yml
  format: yaml
  label: Parallel Image Search API
  slug: parallel-ai-image-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-image-search-api-openapi.yml
- filename: parallel-ai-keys-api-openapi.yml
  format: yaml
  label: Parallel Keys API
  slug: parallel-ai-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-keys-api-openapi.yml
- filename: parallel-ai-place-search-api-openapi.yml
  format: yaml
  label: Parallel Place Search API
  slug: parallel-ai-place-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-place-search-api-openapi.yml
- filename: parallel-ai-usage-api-openapi.yml
  format: yaml
  label: Parallel Usage API
  slug: parallel-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-usage-api-openapi.yml
- filename: parallel-ai-tasks-api-openapi.yml
  format: yaml
  label: Parallel Tasks API
  slug: parallel-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parallel-ai/openapi/parallel-ai-tasks-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Parallel Web Systems
    text: Parallel Web Systems SOC 2 Type 2 Report 2.25.26.pdf
    type: SOC 2 Type 2 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Parallel Web Systems
    text: Parallel Web Systems SOC 3 Report 2.25.26.pdf
    type: SOC 3 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Parallel Web Systems
    text: Parallel Web Systems HIPAA Report 2.25.26.pdf
    type: HIPAA report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance listing
  trust_center:
    url: https://trust.parallel.ai/
frameworks:
- GDPR
- HIPAA
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Parallel
provenance_date: '2026-11-10'
provider_name: Parallel
provider_slug: parallel-ai
slug: parallel-ai-compliance
source_date: '2026-11-10'
source_filename: parallel-ai-compliance.yml
source_heading: Compliance
source_page: https://trust.parallel.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Parallel\naid: parallel-ai\nurl: https://trust.parallel.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/parallel-trust-center.yml\ntrust_center:\n  url: https://trust.parallel.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Parallel Web Systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Parallel Web Systems SOC 2 Type 2 Report 2.25.26.pdf\n- framework: SOC3\n  type: SOC 3 report\n  scope: Parallel Web Systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Parallel Web Systems SOC 3 Report 2.25.26.pdf\n- framework: HIPAA\n\
  \  type: HIPAA report\n  scope: Parallel Web Systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Parallel Web Systems HIPAA Report 2.25.26.pdf\n- framework: GDPR\n  type: compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/parallel-ai/compliance/parallel-ai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Parallel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Web Search
- Agents
- Deep Research
- Web Extraction
- Data Enrichment
- Web Monitoring
- LLM Tools
- A2A
- AI Agents
- MCP
- Agent Skills
- Content Extraction
- Entity Resolution
---
