---
api_specs:
- filename: pinecone-api-keys-api-openapi.yml
  format: yaml
  label: Pinecone API Keys API
  slug: pinecone-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-api-keys-api-openapi.yml
- filename: pinecone-bulk-operations-api-openapi.yml
  format: yaml
  label: Pinecone Bulk Operations API
  slug: pinecone-bulk-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-bulk-operations-api-openapi.yml
- filename: pinecone-inference-api-openapi.yml
  format: yaml
  label: Pinecone Inference API
  slug: pinecone-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-inference-api-openapi.yml
- filename: pinecone-manage-assistants-api-openapi.yml
  format: yaml
  label: Pinecone Manage Assistants API
  slug: pinecone-manage-assistants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-manage-assistants-api-openapi.yml
- filename: pinecone-manage-indexes-api-openapi.yml
  format: yaml
  label: Pinecone Manage Indexes API
  slug: pinecone-manage-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-manage-indexes-api-openapi.yml
- filename: pinecone-namespace-operations-api-openapi.yml
  format: yaml
  label: Pinecone Namespace Operations API
  slug: pinecone-namespace-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-namespace-operations-api-openapi.yml
- filename: pinecone-organizations-api-openapi.yml
  format: yaml
  label: Pinecone Organizations API
  slug: pinecone-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-organizations-api-openapi.yml
- filename: pinecone-projects-api-openapi.yml
  format: yaml
  label: Pinecone Projects API
  slug: pinecone-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-projects-api-openapi.yml
- filename: pinecone-vector-operations-api-openapi.yml
  format: yaml
  label: Pinecone Vector Operations API
  slug: pinecone-vector-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinecone/openapi/pinecone-vector-operations-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certificate
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: Pinecone Systems Inc. SOC2 Type II 2025 -Final report.pdf
    type: SOC 2 Type II report
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance statement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Pinecone - HIPAA Completion Letter.docx (1).pdf
    type: completion letter
  trust_center:
    url: https://trust.pinecone.io/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pinecone
provenance_date: '2026-11-10'
provider_name: Pinecone
provider_slug: pinecone
slug: pinecone-compliance
source_date: '2026-11-10'
source_filename: pinecone-compliance.yml
source_heading: Compliance
source_page: https://trust.pinecone.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pinecone\naid: pinecone\nurl: https://trust.pinecone.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pinecone-trust-center.yml\ntrust_center:\n  url: https://trust.pinecone.io/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: Pinecone Systems Inc. SOC2 Type II 2025 -Final report.pdf\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: completion letter\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pinecone - HIPAA Completion Letter.docx (1).pdf\n"
source_yaml_url: https://artifacts.apis.io/pinecone/compliance/pinecone-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Pinecone's own page on 2026-11-10.
synthetic: false
tags:
- Vector Search
- Artificial Intelligence
- Embeddings
- RAG
- Database
- A2A
---
