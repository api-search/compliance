---
api_specs:
- filename: chroma-system-api-openapi.yml
  format: yaml
  label: Chroma System API
  slug: chroma-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chroma/openapi/chroma-system-api-openapi.yml
- filename: chroma-authentication-api-openapi.yml
  format: yaml
  label: Chroma Authentication API
  slug: chroma-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chroma/openapi/chroma-authentication-api-openapi.yml
- filename: chroma-collection-api-openapi.yml
  format: yaml
  label: Chroma Collection API
  slug: chroma-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chroma/openapi/chroma-collection-api-openapi.yml
- filename: chroma-database-api-openapi.yml
  format: yaml
  label: Chroma Database API
  slug: chroma-database-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chroma/openapi/chroma-database-api-openapi.yml
- filename: chroma-function-api-openapi.yml
  format: yaml
  label: Chroma Function API
  slug: chroma-function-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chroma/openapi/chroma-function-api-openapi.yml
- filename: chroma-record-api-openapi.yml
  format: yaml
  label: Chroma Record API
  slug: chroma-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chroma/openapi/chroma-record-api-openapi.yml
- filename: chroma-tenant-api-openapi.yml
  format: yaml
  label: Chroma Tenant API
  slug: chroma-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chroma/openapi/chroma-tenant-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Chroma Cloud security program
    text: Chroma Cloud has successfully completed a SOC 2 Type II examination.
    type: SOC 2 Type II examination
  trust_center:
    url: https://www.trychroma.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Chroma
provenance_date: '2026-11-09'
provider_name: Chroma
provider_slug: chroma
slug: chroma-compliance
source_date: '2026-11-09'
source_filename: chroma-compliance.yml
source_heading: Compliance
source_page: https://www.trychroma.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Chroma\naid: chroma\nurl: https://www.trychroma.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/chroma-trust-center.yml\ntrust_center:\n  url: https://www.trychroma.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: Chroma Cloud security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Chroma Cloud has successfully completed a SOC 2 Type II examination.\n"
source_yaml_url: https://artifacts.apis.io/chroma/compliance/chroma-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Chroma's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- AI-native
- Apache 2.0
- Cloud
- Embeddings
- Hybrid Search
- JavaScript
- LLM
- Machine Learning
- Multi-Modal
- Open Source
- Python
- RAG
- Retrieval
- SDK
- Search
- Serverless
- TypeScript
- Vector Search
- Database
---
