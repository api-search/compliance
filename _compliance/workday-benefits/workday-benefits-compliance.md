---
api_specs:
- filename: workday-benefits-benefit-enrollments-api-openapi.yml
  format: yaml
  label: Workday Benefits Benefit Enrollments API
  slug: workday-benefits-benefit-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-benefit-enrollments-api-openapi.yml
- filename: workday-benefits-benefit-events-api-openapi.yml
  format: yaml
  label: Workday Benefits Benefit Events API
  slug: workday-benefits-benefit-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-benefit-events-api-openapi.yml
- filename: workday-benefits-benefit-plans-api-openapi.yml
  format: yaml
  label: Workday Benefits Benefit Plans API
  slug: workday-benefits-benefit-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-benefit-plans-api-openapi.yml
- filename: workday-benefits-dependents-api-openapi.yml
  format: yaml
  label: Workday Benefits Dependents API
  slug: workday-benefits-dependents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-dependents-api-openapi.yml
- filename: workday-benefits-employee-benefits-api-openapi.yml
  format: yaml
  label: Workday Benefits Employee Benefits API
  slug: workday-benefits-employee-benefits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-employee-benefits-api-openapi.yml
- filename: workday-benefits-time-off-plans-api-openapi.yml
  format: yaml
  label: Workday Benefits Time Off Plans API
  slug: workday-benefits-time-off-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-time-off-plans-api-openapi.yml
- filename: workday-benefits-06-15-2024-api-openapi.yml
  format: yaml
  label: Workday Benefits 06/15/2024 API
  slug: workday-benefits-06-15-2024-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-06-15-2024-api-openapi.yml
- filename: workday-benefits-06-15-2026-api-openapi.yml
  format: yaml
  label: Workday Benefits 06/15/2026 API
  slug: workday-benefits-06-15-2026-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-06-15-2026-api-openapi.yml
- filename: workday-benefits-06-30-2026-api-openapi.yml
  format: yaml
  label: Workday Benefits 06/30/2026 API
  slug: workday-benefits-06-30-2026-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-06-30-2026-api-openapi.yml
- filename: workday-benefits-08-17-2026-api-openapi.yml
  format: yaml
  label: Workday Benefits 08/17/2026 API
  slug: workday-benefits-08-17-2026-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-08-17-2026-api-openapi.yml
- filename: workday-benefits-09-09-2023-api-openapi.yml
  format: yaml
  label: Workday Benefits 09/09/2023 API
  slug: workday-benefits-09-09-2023-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-09-09-2023-api-openapi.yml
- filename: workday-benefits-employeeenrollmentevent-api-openapi.yml
  format: yaml
  label: Workday Benefits Employee Enrollment Event API
  slug: workday-benefits-employeeenrollmentevent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-employeeenrollmentevent-api-openapi.yml
- filename: workday-benefits-programs-api-openapi.yml
  format: yaml
  label: Workday Benefits Programs API
  slug: workday-benefits-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-benefits/openapi/workday-benefits-programs-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: Type II
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: null
  trust_center:
    url: https://security.workday.com/
frameworks:
- ISO27001
- NIST-CSF
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Workday Benefits
provenance_date: '2026-11-10'
provider_name: Workday Benefits
provider_slug: workday-benefits
slug: workday-benefits-compliance
source_date: '2026-11-10'
source_filename: workday-benefits-compliance.yml
source_heading: Compliance
source_page: https://security.workday.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workday Benefits\naid: workday-benefits\nurl: https://security.workday.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/workday-benefits-trust-center.yml\ntrust_center:\n  url: https://security.workday.com/\nattestations:\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: NIST-CSF\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n"
source_yaml_url: https://artifacts.apis.io/workday-benefits/compliance/workday-benefits-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Workday Benefits's own page on 2026-11-10.
synthetic: false
tags:
- Benefits
- Human Resources
- HCM
- Enterprise
- Payroll
- Employee Benefits
- SOAP
- OpenAPI
---
