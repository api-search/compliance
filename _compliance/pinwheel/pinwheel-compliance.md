---
api_specs:
- filename: pinwheel-accounts-api-openapi.yml
  format: yaml
  label: Pinwheel Accounts API
  slug: pinwheel-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-accounts-api-openapi.yml
- filename: pinwheel-api-keys-api-openapi.yml
  format: yaml
  label: Pinwheel API Keys API
  slug: pinwheel-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-api-keys-api-openapi.yml
- filename: pinwheel-company-connect-api-openapi.yml
  format: yaml
  label: Pinwheel Company Connect API
  slug: pinwheel-company-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-company-connect-api-openapi.yml
- filename: pinwheel-direct-deposit-allocations-api-openapi.yml
  format: yaml
  label: Pinwheel Direct Deposit Allocations API
  slug: pinwheel-direct-deposit-allocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-direct-deposit-allocations-api-openapi.yml
- filename: pinwheel-earnings-stream-api-openapi.yml
  format: yaml
  label: Pinwheel Earnings Stream API
  slug: pinwheel-earnings-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-earnings-stream-api-openapi.yml
- filename: pinwheel-employers-and-platforms-api-openapi.yml
  format: yaml
  label: Pinwheel Employers and Platforms API
  slug: pinwheel-employers-and-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-employers-and-platforms-api-openapi.yml
- filename: pinwheel-end-users-api-openapi.yml
  format: yaml
  label: Pinwheel End Users API
  slug: pinwheel-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-end-users-api-openapi.yml
- filename: pinwheel-income-and-employment-api-openapi.yml
  format: yaml
  label: Pinwheel Income and Employment API
  slug: pinwheel-income-and-employment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-income-and-employment-api-openapi.yml
- filename: pinwheel-jobs-api-openapi.yml
  format: yaml
  label: Pinwheel Jobs API
  slug: pinwheel-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-jobs-api-openapi.yml
- filename: pinwheel-link-tokens-api-openapi.yml
  format: yaml
  label: Pinwheel Link Tokens API
  slug: pinwheel-link-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-link-tokens-api-openapi.yml
- filename: pinwheel-sandbox-api-openapi.yml
  format: yaml
  label: Pinwheel Sandbox API
  slug: pinwheel-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-sandbox-api-openapi.yml
- filename: pinwheel-tax-forms-api-openapi.yml
  format: yaml
  label: Pinwheel Tax Forms API
  slug: pinwheel-tax-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-tax-forms-api-openapi.yml
- filename: pinwheel-verification-reports-api-openapi.yml
  format: yaml
  label: Pinwheel Verification Reports API
  slug: pinwheel-verification-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-verification-reports-api-openapi.yml
- filename: pinwheel-webhooks-api-openapi.yml
  format: yaml
  label: Pinwheel Webhooks API
  slug: pinwheel-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinwheel/openapi/pinwheel-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: From our Trust Center you can request SOC 2, ISO 27001 and PCI DSS Level 1 compliance reports and other security related documentation.
    type: SOC 2 Type 2 report
  - framework: ISO27001
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: ISO 27001:2022 Certificate (2026)
    type: ISO 27001:2022 certificate
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PCI DSS Level 1 Attestation of Compliance
    type: PCI DSS Level 1 Attestation of Compliance
  trust_center:
    url: https://trust.pinwheelapi.com/
frameworks:
- ISO27001
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pinwheel
provenance_date: '2026-11-10'
provider_name: Pinwheel
provider_slug: pinwheel
slug: pinwheel-compliance
source_date: '2026-11-10'
source_filename: pinwheel-compliance.yml
source_heading: Compliance
source_page: https://trust.pinwheelapi.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pinwheel\naid: pinwheel\nurl: https://trust.pinwheelapi.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pinwheel-trust-center.yml\ntrust_center:\n  url: https://trust.pinwheelapi.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: From our Trust Center you can request SOC 2, ISO 27001 and PCI DSS Level 1 compliance reports and other\n    security related documentation.\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n\
  \  text: ISO 27001:2022 Certificate (2026)\n- framework: PCI-DSS\n  type: PCI DSS Level 1 Attestation of Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI DSS Level 1 Attestation of Compliance\n"
source_yaml_url: https://artifacts.apis.io/pinwheel/compliance/pinwheel-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Pinwheel's own page on 2026-11-10.
synthetic: false
tags:
- Payroll
- Direct Deposit
- Income Verification
- Employment
- Tax Forms
- Fintech
- Open Finance
- Bill Switching
- Financial Data
---
