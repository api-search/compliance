---
api_specs:
- filename: truv-admin-api-openapi.yml
  format: yaml
  label: Truv Admin API
  slug: truv-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-admin-api-openapi.yml
- filename: truv-banking-api-openapi.yml
  format: yaml
  label: Truv Banking API
  slug: truv-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-banking-api-openapi.yml
- filename: truv-bridge-tokens-api-openapi.yml
  format: yaml
  label: Truv Bridge Tokens API
  slug: truv-bridge-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-bridge-tokens-api-openapi.yml
- filename: truv-companies-providers-api-openapi.yml
  format: yaml
  label: Truv Companies & Providers API
  slug: truv-companies-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-companies-providers-api-openapi.yml
- filename: truv-direct-deposit-api-openapi.yml
  format: yaml
  label: Truv Direct Deposit API
  slug: truv-direct-deposit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-direct-deposit-api-openapi.yml
- filename: truv-employment-api-openapi.yml
  format: yaml
  label: Truv Employment API
  slug: truv-employment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-employment-api-openapi.yml
- filename: truv-identity-api-openapi.yml
  format: yaml
  label: Truv Identity API
  slug: truv-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-identity-api-openapi.yml
- filename: truv-income-api-openapi.yml
  format: yaml
  label: Truv Income API
  slug: truv-income-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-income-api-openapi.yml
- filename: truv-insurance-api-openapi.yml
  format: yaml
  label: Truv Insurance API
  slug: truv-insurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-insurance-api-openapi.yml
- filename: truv-links-api-openapi.yml
  format: yaml
  label: Truv Links API
  slug: truv-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-links-api-openapi.yml
- filename: truv-orders-api-openapi.yml
  format: yaml
  label: Truv Orders API
  slug: truv-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-orders-api-openapi.yml
- filename: truv-pay-statements-api-openapi.yml
  format: yaml
  label: Truv Pay Statements API
  slug: truv-pay-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-pay-statements-api-openapi.yml
- filename: truv-payroll-shifts-api-openapi.yml
  format: yaml
  label: Truv Payroll & Shifts API
  slug: truv-payroll-shifts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-payroll-shifts-api-openapi.yml
- filename: truv-pll-api-openapi.yml
  format: yaml
  label: Truv PLL API
  slug: truv-pll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-pll-api-openapi.yml
- filename: truv-scoring-api-openapi.yml
  format: yaml
  label: Truv Scoring API
  slug: truv-scoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-scoring-api-openapi.yml
- filename: truv-tasks-api-openapi.yml
  format: yaml
  label: Truv Tasks API
  slug: truv-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-tasks-api-openapi.yml
- filename: truv-tax-api-openapi.yml
  format: yaml
  label: Truv Tax API
  slug: truv-tax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-tax-api-openapi.yml
- filename: truv-templates-api-openapi.yml
  format: yaml
  label: Truv Templates API
  slug: truv-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-templates-api-openapi.yml
- filename: truv-users-api-openapi.yml
  format: yaml
  label: Truv Users API
  slug: truv-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-users-api-openapi.yml
- filename: truv-webhooks-api-openapi.yml
  format: yaml
  label: Truv Webhooks API
  slug: truv-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truv/openapi/truv-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Truv platform
    text: want to request our SOC2 Type II report, we’d be happy to connect
    type: SOC 2 Type II certification
  trust_center:
    url: https://truv.com/commitment-to-security-and-privacy
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Truv
provenance_date: '2026-11-10'
provider_name: Truv
provider_slug: truv
slug: truv-compliance
source_date: '2026-11-10'
source_filename: truv-compliance.yml
source_heading: Compliance
source_page: https://truv.com/commitment-to-security-and-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Truv\naid: truv\nurl: https://truv.com/commitment-to-security-and-privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/truv-trust-center.yml\ntrust_center:\n  url: https://truv.com/commitment-to-security-and-privacy\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: Truv platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: want to request our SOC2 Type II report, we’d be happy to connect\n"
source_yaml_url: https://artifacts.apis.io/truv/compliance/truv-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Truv's own page on 2026-11-10.
synthetic: false
tags:
- Income Verification
- Employment Verification
- Payroll
- Direct Deposit
- Consumer-Permissioned Data
- Fintech
---
