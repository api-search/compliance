---
api_specs:
- filename: idanalyzer-account-api-openapi.yml
  format: yaml
  label: ID Analyzer Account API
  slug: idanalyzer-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-account-api-openapi.yml
- filename: idanalyzer-aml-api-openapi.yml
  format: yaml
  label: ID Analyzer AML API
  slug: idanalyzer-aml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-aml-api-openapi.yml
- filename: idanalyzer-biometric-api-openapi.yml
  format: yaml
  label: ID Analyzer Biometric API
  slug: idanalyzer-biometric-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-biometric-api-openapi.yml
- filename: idanalyzer-contract-api-openapi.yml
  format: yaml
  label: ID Analyzer Contract API
  slug: idanalyzer-contract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-contract-api-openapi.yml
- filename: idanalyzer-docupass-api-openapi.yml
  format: yaml
  label: ID Analyzer Docupass API
  slug: idanalyzer-docupass-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-docupass-api-openapi.yml
- filename: idanalyzer-profile-api-openapi.yml
  format: yaml
  label: ID Analyzer Profile API
  slug: idanalyzer-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-profile-api-openapi.yml
- filename: idanalyzer-scanner-api-openapi.yml
  format: yaml
  label: ID Analyzer Scanner API
  slug: idanalyzer-scanner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-scanner-api-openapi.yml
- filename: idanalyzer-transaction-api-openapi.yml
  format: yaml
  label: ID Analyzer Transaction API
  slug: idanalyzer-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-transaction-api-openapi.yml
- filename: idanalyzer-webhook-api-openapi.yml
  format: yaml
  label: ID Analyzer Webhook API
  slug: idanalyzer-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idanalyzer/openapi/idanalyzer-webhook-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: British Standards Institution (BSI)
    period: null
    report_access: on_request
    scope: ID Analyzer platform information-security management system
    text: The ID Analyzer platform is ISO 27001:2022 certified, awarded by the British Standards Institution (BSI).
    type: certification
  trust_center:
    url: https://www.idanalyzer.com/en/security
frameworks:
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ID Analyzer
provenance_date: '2026-11-09'
provider_name: ID Analyzer
provider_slug: idanalyzer
slug: idanalyzer-compliance
source_date: '2026-11-09'
source_filename: idanalyzer-compliance.yml
source_heading: Compliance
source_page: https://www.idanalyzer.com/en/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ID Analyzer\naid: idanalyzer\nurl: https://www.idanalyzer.com/en/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/idanalyzer-trust-center.yml\ntrust_center:\n  url: https://www.idanalyzer.com/en/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: ID Analyzer platform information-security management system\n  period: null\n  issuer: British Standards Institution (BSI)\n  report_access: on_request\n  text: The ID Analyzer platform is ISO 27001:2022 certified, awarded by the British Standards Institution (BSI).\n"
source_yaml_url: https://artifacts.apis.io/idanalyzer/compliance/idanalyzer-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from ID Analyzer's own page on 2026-11-09.
synthetic: false
tags:
- Identity Verification
- KYC
- AML
- Document OCR
- Biometrics
- Face Matching
- Fraud Prevention
- Passport
- Driver License
- Liveness Detection
---
