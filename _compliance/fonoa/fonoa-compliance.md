---
api_specs:
- filename: fonoa-lookup-v2-api-openapi.yml
  format: yaml
  label: Fonoa Lookup V2 API
  slug: fonoa-lookup-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fonoa/openapi/fonoa-lookup-v2-api-openapi.yml
- filename: fonoa-onboarding-api-openapi.yml
  format: yaml
  label: Fonoa Onboarding API
  slug: fonoa-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fonoa/openapi/fonoa-onboarding-api-openapi.yml
- filename: fonoa-tax-api-openapi.yml
  format: yaml
  label: Fonoa Tax API
  slug: fonoa-tax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fonoa/openapi/fonoa-tax-api-openapi.yml
- filename: fonoa-transactions-api-openapi.yml
  format: yaml
  label: Fonoa Transactions API
  slug: fonoa-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fonoa/openapi/fonoa-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing, storage and protection
    text: We are GDPR-compliant, prioritizing the privacy and security of personal data.
    type: regulatory compliance statement
  trust_center:
    url: https://www.fonoa.com/resources/security
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fonoa
provenance_date: '2026-11-09'
provider_name: Fonoa
provider_slug: fonoa
slug: fonoa-compliance
source_date: '2026-11-09'
source_filename: fonoa-compliance.yml
source_heading: Compliance
source_page: https://www.fonoa.com/resources/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fonoa\naid: fonoa\nurl: https://www.fonoa.com/resources/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/fonoa-trust-center.yml\ntrust_center:\n  url: https://www.fonoa.com/resources/security\nattestations:\n- framework: GDPR\n  type: regulatory compliance statement\n  scope: personal data processing, storage and protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR-compliant, prioritizing the privacy and security of personal data.\n"
source_yaml_url: https://artifacts.apis.io/fonoa/compliance/fonoa-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Fonoa's own page on 2026-11-09.
synthetic: false
tags:
- Tax
- VAT
- GST
- E-Invoicing
- Tax Automation
- Tax Compliance
- Tax Calculation
- Tax ID Validation
- Invoice Generation
- Global Tax
- Indirect Tax
- Fintech
---
