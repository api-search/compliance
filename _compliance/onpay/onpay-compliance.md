---
api_specs:
- filename: onpay-company-api-openapi.yml
  format: yaml
  label: OnPay Company API
  slug: onpay-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-company-api-openapi.yml
- filename: onpay-deductions-api-openapi.yml
  format: yaml
  label: OnPay Deductions API
  slug: onpay-deductions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-deductions-api-openapi.yml
- filename: onpay-employees-api-openapi.yml
  format: yaml
  label: OnPay Employees API
  slug: onpay-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-employees-api-openapi.yml
- filename: onpay-pay-runs-api-openapi.yml
  format: yaml
  label: OnPay Pay Runs API
  slug: onpay-pay-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-pay-runs-api-openapi.yml
- filename: onpay-reports-api-openapi.yml
  format: yaml
  label: OnPay Reports API
  slug: onpay-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-reports-api-openapi.yml
- filename: onpay-user-api-openapi.yml
  format: yaml
  label: OnPay User API
  slug: onpay-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-user-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA SOC program third-party auditor
    period: null
    report_access: on_request
    scope: client data protection through internal controls
    text: OnPay holds third-party auditor certification with the AICPA’s SOC program and is SOC 2 Type II compliant.
    type: SOC 2 Type II
  trust_center:
    url: https://onpay.com/security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OnPay
provenance_date: '2026-11-10'
provider_name: OnPay
provider_slug: onpay
slug: onpay-compliance
source_date: '2026-11-10'
source_filename: onpay-compliance.yml
source_heading: Compliance
source_page: https://onpay.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OnPay\naid: onpay\nurl: https://onpay.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://onpay.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: client data protection through internal controls\n  period: null\n  issuer: AICPA SOC program third-party auditor\n  report_access: on_request\n  text: OnPay holds third-party auditor certification with the AICPA’s SOC program and is SOC 2 Type II compliant.\n"
source_yaml_url: https://artifacts.apis.io/onpay/compliance/onpay-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from OnPay's own page on 2026-11-10.
synthetic: false
tags:
- Payroll
- Human Resources
- Employee Benefits
- Payroll Tax
- Small Business
- Workforce Management
- Fintech
- Time and Attendance
- retirement-401k
---
