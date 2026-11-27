---
api_specs:
- filename: sensible-io-account-api-openapi.yml
  format: yaml
  label: Sensible Account API
  slug: sensible-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-account-api-openapi.yml
- filename: sensible-io-classify-api-openapi.yml
  format: yaml
  label: Sensible Classify API
  slug: sensible-io-classify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-classify-api-openapi.yml
- filename: sensible-io-configs-api-openapi.yml
  format: yaml
  label: Sensible Configs API
  slug: sensible-io-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-configs-api-openapi.yml
- filename: sensible-io-document-types-api-openapi.yml
  format: yaml
  label: Sensible Document Types API
  slug: sensible-io-document-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-document-types-api-openapi.yml
- filename: sensible-io-documents-api-openapi.yml
  format: yaml
  label: Sensible Documents API
  slug: sensible-io-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-documents-api-openapi.yml
- filename: sensible-io-extract-api-openapi.yml
  format: yaml
  label: Sensible Extract API
  slug: sensible-io-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-extract-api-openapi.yml
- filename: sensible-io-reference-documents-api-openapi.yml
  format: yaml
  label: Sensible Reference Documents API
  slug: sensible-io-reference-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-reference-documents-api-openapi.yml
- filename: sensible-io-upload-api-openapi.yml
  format: yaml
  label: Sensible Upload API
  slug: sensible-io-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensible-io/openapi/sensible-io-upload-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA compliance
    type: compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliance
    type: compliance
  trust_center:
    url: https://www.sensible.so/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sensible
provenance_date: '2026-11-10'
provider_name: Sensible
provider_slug: sensible-io
slug: sensible-io-compliance
source_date: '2026-11-10'
source_filename: sensible-io-compliance.yml
source_heading: Compliance
source_page: https://www.sensible.so/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sensible\naid: sensible-io\nurl: https://www.sensible.so/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sensible-io-trust-center.yml\ntrust_center:\n  url: https://www.sensible.so/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliance\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ GDPR compliance\n"
source_yaml_url: https://artifacts.apis.io/sensible-io/compliance/sensible-io-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sensible's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Document AI
- Intelligent Document Processing
- Extraction
- LLM
- SenseML
- PDF
---
