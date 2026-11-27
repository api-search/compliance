---
api_specs:
- filename: pactflow-ai-api-openapi.yml
  format: yaml
  label: PactFlow AI API
  slug: pactflow-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-ai-api-openapi.yml
- filename: pactflow-drift-api-openapi.yml
  format: yaml
  label: PactFlow Drift API
  slug: pactflow-drift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-drift-api-openapi.yml
- filename: pactflow-orders-api-openapi.yml
  format: yaml
  label: PactFlow Orders API
  slug: pactflow-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-orders-api-openapi.yml
- filename: pactflow-pact-foundation-api-openapi.yml
  format: yaml
  label: PactFlow Pact Foundation API
  slug: pactflow-pact-foundation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-pact-foundation-api-openapi.yml
- filename: pactflow-pacts-api-openapi.yml
  format: yaml
  label: PactFlow Pacts API
  slug: pactflow-pacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-pacts-api-openapi.yml
- filename: pactflow-product-api-openapi.yml
  format: yaml
  label: PactFlow Product API
  slug: pactflow-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-product-api-openapi.yml
- filename: pactflow-products-api-openapi.yml
  format: yaml
  label: PactFlow Products API
  slug: pactflow-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-products-api-openapi.yml
- filename: pactflow-test-api-openapi.yml
  format: yaml
  label: PactFlow Test API
  slug: pactflow-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pactflow/openapi/pactflow-test-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management system (ISMS)
    text: Systems and Organization Control 2 - Type 1 Standard - Information Security Management system (ISMS)
    type: Type 1
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We comply with policies based on CIS IG 1.
    type: CIS IG 1
  trust_center:
    url: https://pactflow.io/security/
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PactFlow
provenance_date: '2026-11-10'
provider_name: PactFlow
provider_slug: pactflow
slug: pactflow-compliance
source_date: '2026-11-10'
source_filename: pactflow-compliance.yml
source_heading: Compliance
source_page: https://pactflow.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PactFlow\naid: pactflow\nurl: https://pactflow.io/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://pactflow.io/security/\nattestations:\n- framework: SOC2\n  type: Type 1\n  scope: Information Security Management system (ISMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Systems and Organization Control 2 - Type 1 Standard - Information Security Management system (ISMS)\n- framework: other\n  type: CIS IG 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with policies based on CIS IG 1.\n"
source_yaml_url: https://artifacts.apis.io/pactflow/compliance/pactflow-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from PactFlow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Testing
- Contract Testing
- Microservices
- CI/CD
---
