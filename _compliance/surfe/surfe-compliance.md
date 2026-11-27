---
api_specs:
- filename: surfe-account-api-openapi.yml
  format: yaml
  label: Surfe Account API
  slug: surfe-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-account-api-openapi.yml
- filename: surfe-companies-api-openapi.yml
  format: yaml
  label: Surfe Companies API
  slug: surfe-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-companies-api-openapi.yml
- filename: surfe-people-api-openapi.yml
  format: yaml
  label: Surfe People API
  slug: surfe-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-people-api-openapi.yml
- filename: surfe-recommendations-api-openapi.yml
  format: yaml
  label: Surfe Recommendations API
  slug: surfe-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-recommendations-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management system
    text: Our information security management system is independently audited and certified to the ISO 27001 standard.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing
    text: Surfe processes personal data in accordance with GDPR and follows established data protection and privacy practices.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: personal data rights of California residents
    text: Surfe complies with California's Consumer Privacy Act, safeguarding the personal data rights of California residents.
    type: compliance
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Compliant
    type: compliance
  trust_center:
    url: https://www.surfe.com/trust-center
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Surfe
provenance_date: '2026-11-10'
provider_name: Surfe
provider_slug: surfe
slug: surfe-compliance
source_date: '2026-11-10'
source_filename: surfe-compliance.yml
source_heading: Compliance
source_page: https://www.surfe.com/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Surfe\naid: surfe\nurl: https://www.surfe.com/trust-center\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.surfe.com/trust-center\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Our information security management system is independently audited and certified to the ISO 27001 standard.\n- framework: GDPR\n  type: compliance\n  scope: personal data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Surfe processes personal data in accordance\
  \ with GDPR and follows established data protection and privacy\n    practices.\n- framework: CCPA\n  type: compliance\n  scope: personal data rights of California residents\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Surfe complies with California's Consumer Privacy Act, safeguarding the personal data rights of California\n    residents.\n- framework: SOC2\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/surfe/compliance/surfe-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Surfe's own page on 2026-11-10.
synthetic: false
tags:
- B2B Data
- Contact Data
- Sales Intelligence
- Data Enrichment
- Lead Generation
- CRM
- Prospecting
---
