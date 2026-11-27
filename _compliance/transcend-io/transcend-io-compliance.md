---
api_specs:
- filename: transcend-io-consent-api-openapi.yml
  format: yaml
  label: Transcend Consent API
  slug: transcend-io-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-consent-api-openapi.yml
- filename: transcend-io-custom-integration-api-openapi.yml
  format: yaml
  label: Transcend Custom Integration API
  slug: transcend-io-custom-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-custom-integration-api-openapi.yml
- filename: transcend-io-data-subject-request-api-openapi.yml
  format: yaml
  label: Transcend Data Subject Request API
  slug: transcend-io-data-subject-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-data-subject-request-api-openapi.yml
- filename: transcend-io-llm-classifier-api-openapi.yml
  format: yaml
  label: Transcend LLM Classifier API
  slug: transcend-io-llm-classifier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-llm-classifier-api-openapi.yml
- filename: transcend-io-preferences-api-openapi.yml
  format: yaml
  label: Transcend Preferences API
  slug: transcend-io-preferences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-preferences-api-openapi.yml
- filename: transcend-io-preflight-api-openapi.yml
  format: yaml
  label: Transcend Preflight API
  slug: transcend-io-preflight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-preflight-api-openapi.yml
- filename: transcend-io-public-keys-api-openapi.yml
  format: yaml
  label: Transcend Public Keys API
  slug: transcend-io-public-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-public-keys-api-openapi.yml
- filename: transcend-io-transcend-api-api-openapi.yml
  format: yaml
  label: Transcend API
  slug: transcend-io-transcend-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcend-io/openapi/transcend-io-transcend-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: not stated
    period: null
    report_access: unstated
    scope: not stated
    text: Transcend regularly attains SOC 2 (Type II) and ISO 27001 compliance
    type: SOC 2 (Type II)
  - framework: ISO27001
    issuer: not stated
    period: null
    report_access: unstated
    scope: not stated
    text: Transcend regularly attains SOC 2 (Type II) and ISO 27001 compliance
    type: ISO 27001 compliance
  trust_center:
    url: https://transcend.io/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Transcend
provenance_date: '2026-11-10'
provider_name: Transcend
provider_slug: transcend-io
slug: transcend-io-compliance
source_date: '2026-11-10'
source_filename: transcend-io-compliance.yml
source_heading: Compliance
source_page: https://transcend.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Transcend\naid: transcend-io\nurl: https://transcend.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/transcend-io-trust-center.yml\ntrust_center:\n  url: https://transcend.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 (Type II)\n  scope: not stated\n  period: null\n  issuer: not stated\n  report_access: unstated\n  text: Transcend regularly attains SOC 2 (Type II) and ISO 27001 compliance\n- framework: ISO27001\n  type: ISO 27001 compliance\n  scope: not stated\n  period: null\n  issuer: not stated\n  report_access: unstated\n  text: Transcend regularly attains SOC 2 (Type\
  \ II) and ISO 27001 compliance\n"
source_yaml_url: https://artifacts.apis.io/transcend-io/compliance/transcend-io-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Transcend's own page on 2026-11-10.
synthetic: false
tags:
- Transcend
- Privacy
- Data Governance
- Consent
- Preference Management
- DSR
- Data Inventory
- AI Governance
- GDPR
- CCPA
- Compliance
- Webhook
- GraphQL
- MCP
- SDK
- Terraform
- Helm
---
