---
api_specs:
- filename: cable-alerts-api-openapi.yml
  format: yaml
  label: Cable Alerts API
  slug: cable-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-alerts-api-openapi.yml
- filename: cable-authentication-api-openapi.yml
  format: yaml
  label: Cable Authentication API
  slug: cable-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-authentication-api-openapi.yml
- filename: cable-business-api-openapi.yml
  format: yaml
  label: Cable Business API
  slug: cable-business-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-business-api-openapi.yml
- filename: cable-checks-api-openapi.yml
  format: yaml
  label: Cable Checks API
  slug: cable-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-checks-api-openapi.yml
- filename: cable-company-api-openapi.yml
  format: yaml
  label: Cable Company API
  slug: cable-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-company-api-openapi.yml
- filename: cable-customersar-api-openapi.yml
  format: yaml
  label: Cable Customer Sar API
  slug: cable-customersar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-customersar-api-openapi.yml
- filename: cable-helper-api-openapi.yml
  format: yaml
  label: Cable Helper API
  slug: cable-helper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-helper-api-openapi.yml
- filename: cable-onboardingflow-api-openapi.yml
  format: yaml
  label: Cable Onboarding Flow API
  slug: cable-onboardingflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-onboardingflow-api-openapi.yml
- filename: cable-person-api-openapi.yml
  format: yaml
  label: Cable Person API
  slug: cable-person-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-person-api-openapi.yml
- filename: cable-retail-api-openapi.yml
  format: yaml
  label: Cable Retail API
  slug: cable-retail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-retail-api-openapi.yml
- filename: cable-screening-api-openapi.yml
  format: yaml
  label: Cable Screening API
  slug: cable-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-screening-api-openapi.yml
- filename: cable-suspiciousactivities-api-openapi.yml
  format: yaml
  label: Cable Suspicious Activities API
  slug: cable-suspiciousactivities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-suspiciousactivities-api-openapi.yml
- filename: cable-transactionalerts-api-openapi.yml
  format: yaml
  label: Cable Transaction Alerts API
  slug: cable-transactionalerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-transactionalerts-api-openapi.yml
- filename: cable-transactionchecks-api-openapi.yml
  format: yaml
  label: Cable Transaction Checks API
  slug: cable-transactionchecks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-transactionchecks-api-openapi.yml
- filename: cable-transactions-api-openapi.yml
  format: yaml
  label: Cable Transactions API
  slug: cable-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-transactions-api-openapi.yml
- filename: cable-transactionsuspiciousactivities-api-openapi.yml
  format: yaml
  label: Cable Transaction Suspicious Activities API
  slug: cable-transactionsuspiciousactivities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-transactionsuspiciousactivities-api-openapi.yml
- filename: cable-upload-api-openapi.yml
  format: yaml
  label: Cable Upload API
  slug: cable-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-upload-api-openapi.yml
- filename: cable-utilities-api-openapi.yml
  format: yaml
  label: Cable Utilities API
  slug: cable-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-utilities-api-openapi.yml
- filename: cable-identity-verification-api-openapi.yml
  format: yaml
  label: Cable Identity Verification API
  slug: cable-identity-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-identity-verification-api-openapi.yml
- filename: cable-risk-assessment-api-openapi.yml
  format: yaml
  label: Cable Risk Assessment API
  slug: cable-risk-assessment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cable/openapi/cable-risk-assessment-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Cable is SOC2 Type I certified, demonstrating our dedication to data security.
    type: Type I certification
  trust_center:
    url: https://cable.tech/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cable
provenance_date: '2026-11-09'
provider_name: Cable
provider_slug: cable
slug: cable-compliance
source_date: '2026-11-09'
source_filename: cable-compliance.yml
source_heading: Compliance
source_page: https://cable.tech/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cable\naid: cable\nurl: https://cable.tech/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cable-trust-center.yml\ntrust_center:\n  url: https://cable.tech/security\nattestations:\n- framework: SOC2\n  type: Type I certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cable is SOC2 Type I certified, demonstrating our dedication to data security.\n"
source_yaml_url: https://artifacts.apis.io/cable/compliance/cable-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Cable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Financial Crime
- RegTech
- AML
- Transaction Monitoring
- Screening
- Risk Assessment
- Banking
- Fintech
---
