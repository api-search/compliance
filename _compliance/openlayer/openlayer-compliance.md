---
api_specs:
- filename: openlayer-commits-api-openapi.yml
  format: yaml
  label: Openlayer Commits API
  slug: openlayer-commits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlayer/openapi/openlayer-commits-api-openapi.yml
- filename: openlayer-data-stream-api-openapi.yml
  format: yaml
  label: Openlayer Data Stream API
  slug: openlayer-data-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlayer/openapi/openlayer-data-stream-api-openapi.yml
- filename: openlayer-inference-pipelines-api-openapi.yml
  format: yaml
  label: Openlayer Inference Pipelines API
  slug: openlayer-inference-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlayer/openapi/openlayer-inference-pipelines-api-openapi.yml
- filename: openlayer-projects-api-openapi.yml
  format: yaml
  label: Openlayer Projects API
  slug: openlayer-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlayer/openapi/openlayer-projects-api-openapi.yml
- filename: openlayer-storage-api-openapi.yml
  format: yaml
  label: Openlayer Storage API
  slug: openlayer-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlayer/openapi/openlayer-storage-api-openapi.yml
- filename: openlayer-tests-api-openapi.yml
  format: yaml
  label: Openlayer Tests API
  slug: openlayer-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlayer/openapi/openlayer-tests-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Openlayer platform
    text: Security documentation, including details on certifications, architecture, and penetration testing, is available on request.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Openlayer
    text: Openlayer is also GDPR compliant and supports HIPAA-aligned use cases.
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Openlayer
    text: supports HIPAA-aligned use cases
    type: HIPAA-aligned use cases
  trust_center:
    url: https://www.openlayer.com/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Openlayer
provenance_date: '2026-11-10'
provider_name: Openlayer
provider_slug: openlayer
slug: openlayer-compliance
source_date: '2026-11-10'
source_filename: openlayer-compliance.yml
source_heading: Compliance
source_page: https://www.openlayer.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Openlayer\naid: openlayer\nurl: https://www.openlayer.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/openlayer-trust-center.yml\ntrust_center:\n  url: https://www.openlayer.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Openlayer platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Security documentation, including details on certifications, architecture, and penetration testing, is available\n    on request.\n- framework: GDPR\n  type: compliance\n  scope: Openlayer\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Openlayer is also GDPR compliant and supports HIPAA-aligned use cases.\n- framework: HIPAA\n  type: HIPAA-aligned use cases\n  scope: Openlayer\n  period: null\n  issuer: null\n  report_access: unstated\n  text: supports HIPAA-aligned use cases\n"
source_yaml_url: https://artifacts.apis.io/openlayer/compliance/openlayer-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Openlayer's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Evaluation
- Testing
- Observability
- LLM
- MLOps
---
