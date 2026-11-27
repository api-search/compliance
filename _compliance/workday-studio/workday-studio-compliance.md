---
api_specs:
- filename: workday-studio-absence-management-api-openapi.yml
  format: yaml
  label: Workday Studio Absence Management API
  slug: workday-studio-absence-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-absence-management-api-openapi.yml
- filename: workday-studio-benefits-administration-api-openapi.yml
  format: yaml
  label: Workday Studio Benefits Administration API
  slug: workday-studio-benefits-administration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-benefits-administration-api-openapi.yml
- filename: workday-studio-compensation-api-openapi.yml
  format: yaml
  label: Workday Studio Compensation API
  slug: workday-studio-compensation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-compensation-api-openapi.yml
- filename: workday-studio-financial-management-api-openapi.yml
  format: yaml
  label: Workday Studio Financial Management API
  slug: workday-studio-financial-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-financial-management-api-openapi.yml
- filename: workday-studio-human-resources-api-openapi.yml
  format: yaml
  label: Workday Studio Human Resources API
  slug: workday-studio-human-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-human-resources-api-openapi.yml
- filename: workday-studio-integration-assemblies-api-openapi.yml
  format: yaml
  label: Workday Studio Integration Assemblies API
  slug: workday-studio-integration-assemblies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-integration-assemblies-api-openapi.yml
- filename: workday-studio-integration-events-api-openapi.yml
  format: yaml
  label: Workday Studio Integration Events API
  slug: workday-studio-integration-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-integration-events-api-openapi.yml
- filename: workday-studio-integration-systems-api-openapi.yml
  format: yaml
  label: Workday Studio Integration Systems API
  slug: workday-studio-integration-systems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-integration-systems-api-openapi.yml
- filename: workday-studio-integration-templates-api-openapi.yml
  format: yaml
  label: Workday Studio Integration Templates API
  slug: workday-studio-integration-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-integration-templates-api-openapi.yml
- filename: workday-studio-launch-parameters-api-openapi.yml
  format: yaml
  label: Workday Studio Launch Parameters API
  slug: workday-studio-launch-parameters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-launch-parameters-api-openapi.yml
- filename: workday-studio-payroll-api-openapi.yml
  format: yaml
  label: Workday Studio Payroll API
  slug: workday-studio-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-payroll-api-openapi.yml
- filename: workday-studio-recruiting-api-openapi.yml
  format: yaml
  label: Workday Studio Recruiting API
  slug: workday-studio-recruiting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-recruiting-api-openapi.yml
- filename: workday-studio-service-directory-api-openapi.yml
  format: yaml
  label: Workday Studio Service Directory API
  slug: workday-studio-service-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-service-directory-api-openapi.yml
- filename: workday-studio-staffing-api-openapi.yml
  format: yaml
  label: Workday Studio Staffing API
  slug: workday-studio-staffing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-staffing-api-openapi.yml
- filename: workday-studio-time-tracking-api-openapi.yml
  format: yaml
  label: Workday Studio Time Tracking API
  slug: workday-studio-time-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workday-studio/openapi/workday-studio-time-tracking-api-openapi.yml
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
    type: aligned with
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: aligned with
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II, and NIST Cybersecurity Framework controls.
    type: aligned with
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
name: Workday Studio
provenance_date: '2026-11-10'
provider_name: Workday Studio
provider_slug: workday-studio
slug: workday-studio-compliance
source_date: '2026-11-10'
source_filename: workday-studio-compliance.yml
source_heading: Compliance
source_page: https://security.workday.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workday Studio\naid: workday-studio\nurl: https://security.workday.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/workday-studio-trust-center.yml\ntrust_center:\n  url: https://security.workday.com/\nattestations:\n- framework: ISO27001\n  type: aligned with\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: SOC2\n  type: aligned with\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n- framework: NIST-CSF\n  type: aligned with\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Workday is engineered on a defense-in-depth security architecture aligned with ISO 27001, SOC 2 Type II,\n    and NIST Cybersecurity Framework controls.\n"
source_yaml_url: https://artifacts.apis.io/workday-studio/compliance/workday-studio-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Workday Studio's own page on 2026-11-10.
synthetic: false
tags:
- Cloud
- Developer Tools
- Development
- Enterprise
- Finance
- Human Resources
- IDE
- Integration
---
