---
api_specs:
- filename: zeroentropy-admin-api-openapi.yml
  format: yaml
  label: ZeroEntropy Admin API
  slug: zeroentropy-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-admin-api-openapi.yml
- filename: zeroentropy-collections-api-openapi.yml
  format: yaml
  label: ZeroEntropy Collections API
  slug: zeroentropy-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-collections-api-openapi.yml
- filename: zeroentropy-documents-api-openapi.yml
  format: yaml
  label: ZeroEntropy Documents API
  slug: zeroentropy-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-documents-api-openapi.yml
- filename: zeroentropy-models-api-openapi.yml
  format: yaml
  label: ZeroEntropy Models API
  slug: zeroentropy-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-models-api-openapi.yml
- filename: zeroentropy-queries-api-openapi.yml
  format: yaml
  label: ZeroEntropy Queries API
  slug: zeroentropy-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-queries-api-openapi.yml
- filename: zeroentropy-status-api-openapi.yml
  format: yaml
  label: ZeroEntropy Status API
  slug: zeroentropy-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-status-api-openapi.yml
- filename: zeroentropy-usage-api-openapi.yml
  format: yaml
  label: ZeroEntropy Usage API
  slug: zeroentropy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II Compliant
    type: SOC 2 Type II Compliant
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: HIPAA Compliant
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Penetration Test Completed
    type: Penetration Test Completed
  trust_center:
    url: https://www.zeroentropy.dev/trust
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ZeroEntropy
provenance_date: '2026-11-10'
provider_name: ZeroEntropy
provider_slug: zeroentropy
slug: zeroentropy-compliance
source_date: '2026-11-10'
source_filename: zeroentropy-compliance.yml
source_heading: Compliance
source_page: https://www.zeroentropy.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ZeroEntropy\naid: zeroentropy\nurl: https://www.zeroentropy.dev/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zeroentropy-trust-center.yml\ntrust_center:\n  url: https://www.zeroentropy.dev/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Compliant\n- framework: HIPAA\n  type: HIPAA Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: other\n  type: Penetration Test Completed\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: on_request\n  text: Penetration Test Completed\n"
source_yaml_url: https://artifacts.apis.io/zeroentropy/compliance/zeroentropy-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from ZeroEntropy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Artificial Intelligence
- Search
- Retrieval
- Embeddings
- Reranking
- RAG
---
