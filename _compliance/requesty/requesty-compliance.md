---
api_specs:
- filename: requesty-api-keys-api-openapi.yml
  format: yaml
  label: Requesty API Keys API
  slug: requesty-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/requesty/openapi/requesty-api-keys-api-openapi.yml
- filename: requesty-embeddings-api-openapi.yml
  format: yaml
  label: Requesty Embeddings API
  slug: requesty-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/requesty/openapi/requesty-embeddings-api-openapi.yml
- filename: requesty-models-api-openapi.yml
  format: yaml
  label: Requesty Models API
  slug: requesty-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/requesty/openapi/requesty-models-api-openapi.yml
- filename: requesty-usage-api-openapi.yml
  format: yaml
  label: Requesty Usage API
  slug: requesty-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/requesty/openapi/requesty-usage-api-openapi.yml
- filename: requesty-chat-completions-api-openapi.yml
  format: yaml
  label: Requesty Chat Completions API
  slug: requesty-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/requesty/openapi/requesty-chat-completions-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Requesty service
    text: We are GDPR compliant, provide a DPA on request, and support EU data residency in Frankfurt.
    type: self-stated compliance claim
  trust_center:
    url: https://www.requesty.ai/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Requesty
provenance_date: '2026-11-10'
provider_name: Requesty
provider_slug: requesty
slug: requesty-compliance
source_date: '2026-11-10'
source_filename: requesty-compliance.yml
source_heading: Compliance
source_page: https://www.requesty.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Requesty\naid: requesty\nurl: https://www.requesty.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/requesty-trust-center.yml\ntrust_center:\n  url: https://www.requesty.ai/security\nattestations:\n- framework: GDPR\n  type: self-stated compliance claim\n  scope: Requesty service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant, provide a DPA on request, and support EU data residency in Frankfurt.\n"
source_yaml_url: https://artifacts.apis.io/requesty/compliance/requesty-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Requesty's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Routing
- Gateways
- Observability
- Real-Time
- A2A
---
