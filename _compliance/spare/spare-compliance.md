---
api_specs:
- filename: spare-account-api-openapi.yml
  format: yaml
  label: Spare Account API
  slug: spare-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-account-api-openapi.yml
- filename: spare-accountinformationreport-api-openapi.yml
  format: yaml
  label: Spare AccountInformationReport API
  slug: spare-accountinformationreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-accountinformationreport-api-openapi.yml
- filename: spare-balance-api-openapi.yml
  format: yaml
  label: Spare Balance API
  slug: spare-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-balance-api-openapi.yml
- filename: spare-beneficiary-api-openapi.yml
  format: yaml
  label: Spare Beneficiary API
  slug: spare-beneficiary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-beneficiary-api-openapi.yml
- filename: spare-cert-api-openapi.yml
  format: yaml
  label: Spare Cert API
  slug: spare-cert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-cert-api-openapi.yml
- filename: spare-connection-api-openapi.yml
  format: yaml
  label: Spare Connection API
  slug: spare-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-connection-api-openapi.yml
- filename: spare-consent-api-openapi.yml
  format: yaml
  label: Spare Consent API
  slug: spare-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-consent-api-openapi.yml
- filename: spare-customer-api-openapi.yml
  format: yaml
  label: Spare Customer API
  slug: spare-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-customer-api-openapi.yml
- filename: spare-parties-api-openapi.yml
  format: yaml
  label: Spare Parties API
  slug: spare-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-parties-api-openapi.yml
- filename: spare-payment-api-openapi.yml
  format: yaml
  label: Spare Payment API
  slug: spare-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-payment-api-openapi.yml
- filename: spare-provider-api-openapi.yml
  format: yaml
  label: Spare Provider API
  slug: spare-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-provider-api-openapi.yml
- filename: spare-request-api-openapi.yml
  format: yaml
  label: Spare Request API
  slug: spare-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-request-api-openapi.yml
- filename: spare-riskreport-api-openapi.yml
  format: yaml
  label: Spare RiskReport API
  slug: spare-riskreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-riskreport-api-openapi.yml
- filename: spare-statement-api-openapi.yml
  format: yaml
  label: Spare Statement API
  slug: spare-statement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-statement-api-openapi.yml
- filename: spare-token-api-openapi.yml
  format: yaml
  label: Spare Token API
  slug: spare-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-token-api-openapi.yml
- filename: spare-transaction-api-openapi.yml
  format: yaml
  label: Spare Transaction API
  slug: spare-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-transaction-api-openapi.yml
- filename: spare-direct-debit-api-openapi.yml
  format: yaml
  label: Spare Direct Debit API
  slug: spare-direct-debit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-direct-debit-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Certified
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certified
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Saudi Arabia SAMA CSF
    text: SAMA CSF Compliant
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: UAE NESA Compliance Framework
    text: NESA Compliance Framework (UAE) Compliant
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: UAE Data Protection Law
    text: UAE Data Protection Law Compliant
    type: compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Saudi Arabia PDPL v2
    text: Saudi Arabia PDPL v2 Compliant
    type: compliance
  trust_center:
    url: https://trust.tryspare.com/
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Spare
provenance_date: '2026-11-10'
provider_name: Spare
provider_slug: spare
slug: spare-compliance
source_date: '2026-11-10'
source_filename: spare-compliance.yml
source_heading: Compliance
source_page: https://trust.tryspare.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Spare\naid: spare\nurl: https://trust.tryspare.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.tryspare.com/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: other\n  type: compliance\n  scope: Saudi Arabia SAMA CSF\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SAMA CSF Compliant\n- framework: other\n \
  \ type: compliance\n  scope: UAE NESA Compliance Framework\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NESA Compliance Framework (UAE) Compliant\n- framework: other\n  type: compliance\n  scope: UAE Data Protection Law\n  period: null\n  issuer: null\n  report_access: unstated\n  text: UAE Data Protection Law Compliant\n- framework: other\n  type: compliance\n  scope: Saudi Arabia PDPL v2\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Saudi Arabia PDPL v2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/spare/compliance/spare-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Spare's own page on 2026-11-10.
synthetic: false
tags:
- Open Banking
- Open Finance
- Account Information
- Payment Initiation
- AISP
- PISP
- Consent
- Bank Data
- Transaction
- Balances
- Payments
- Fintech
- MENA
- Saudi Arabia
- Bahrain
- United Arab Emirates
---
