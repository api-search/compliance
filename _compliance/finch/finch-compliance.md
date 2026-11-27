---
api_specs:
- filename: finch-connect-api-openapi.yml
  format: yaml
  label: Finch Connect API
  slug: finch-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-connect-api-openapi.yml
- filename: finch-benefits-api-openapi.yml
  format: yaml
  label: Finch Benefits API
  slug: finch-benefits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-benefits-api-openapi.yml
- filename: finch-deductions-api-openapi.yml
  format: yaml
  label: Finch Deductions API
  slug: finch-deductions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-deductions-api-openapi.yml
- filename: finch-documents-api-openapi.yml
  format: yaml
  label: Finch Documents API
  slug: finch-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-documents-api-openapi.yml
- filename: finch-management-api-openapi.yml
  format: yaml
  label: Finch Management API
  slug: finch-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-management-api-openapi.yml
- filename: finch-organization-api-openapi.yml
  format: yaml
  label: Finch Organization API
  slug: finch-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-organization-api-openapi.yml
- filename: finch-payroll-api-openapi.yml
  format: yaml
  label: Finch Payroll API
  slug: finch-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-payroll-api-openapi.yml
- filename: finch-sandbox-api-openapi.yml
  format: yaml
  label: Finch Sandbox API
  slug: finch-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finch/openapi/finch-sandbox-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Finch is SOC 2 Type II and CCPA compliant.
    type: SOC 2 Type II
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Finch is SOC 2 Type II and CCPA compliant.
    type: compliance
  trust_center:
    url: https://www.tryfinch.com/company/security
frameworks:
- CCPA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Finch
provenance_date: '2026-11-09'
provider_name: Finch
provider_slug: finch
slug: finch-compliance
source_date: '2026-11-09'
source_filename: finch-compliance.yml
source_heading: Compliance
source_page: https://www.tryfinch.com/company/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Finch\naid: finch\nurl: https://www.tryfinch.com/company/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/finch-trust-center.yml\ntrust_center:\n  url: https://www.tryfinch.com/company/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Finch is SOC 2 Type II and CCPA compliant.\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Finch is SOC 2 Type II and CCPA compliant.\n"
source_yaml_url: https://artifacts.apis.io/finch/compliance/finch-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Finch's own page on 2026-11-09.
synthetic: false
tags:
- Employment
- HRIS
- Payroll
- Benefits
- Human Resources
- Unified API
- Workforce
- Integration
- Employee Benefits
---
