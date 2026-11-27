---
api_specs:
- filename: leapsome-absences-api-openapi.yml
  format: yaml
  label: Leapsome Absences API
  slug: leapsome-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-absences-api-openapi.yml
- filename: leapsome-auth-api-openapi.yml
  format: yaml
  label: Leapsome Auth API
  slug: leapsome-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-auth-api-openapi.yml
- filename: leapsome-documents-api-openapi.yml
  format: yaml
  label: Leapsome Documents API
  slug: leapsome-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-documents-api-openapi.yml
- filename: leapsome-feedback-api-openapi.yml
  format: yaml
  label: Leapsome Feedback API
  slug: leapsome-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-feedback-api-openapi.yml
- filename: leapsome-goals-api-openapi.yml
  format: yaml
  label: Leapsome Goals API
  slug: leapsome-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-goals-api-openapi.yml
- filename: leapsome-groups-api-openapi.yml
  format: yaml
  label: Leapsome Groups API
  slug: leapsome-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-groups-api-openapi.yml
- filename: leapsome-leapsome-api-api-openapi.yml
  format: yaml
  label: Leapsome API
  slug: leapsome-leapsome-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-leapsome-api-api-openapi.yml
- filename: leapsome-payroll-api-openapi.yml
  format: yaml
  label: Leapsome Payroll API
  slug: leapsome-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-payroll-api-openapi.yml
- filename: leapsome-reviews-api-openapi.yml
  format: yaml
  label: Leapsome Reviews API
  slug: leapsome-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-reviews-api-openapi.yml
- filename: leapsome-schemas-api-openapi.yml
  format: yaml
  label: Leapsome Schemas API
  slug: leapsome-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-schemas-api-openapi.yml
- filename: leapsome-users-api-openapi.yml
  format: yaml
  label: Leapsome Users API
  slug: leapsome-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-users-api-openapi.yml
- filename: leapsome-worklocations-api-openapi.yml
  format: yaml
  label: Leapsome Work Locations API
  slug: leapsome-worklocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-worklocations-api-openapi.yml
- filename: leapsome-access-roles-api-openapi.yml
  format: yaml
  label: Leapsome Access Roles API
  slug: leapsome-access-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-access-roles-api-openapi.yml
- filename: leapsome-time-tracking-api-openapi.yml
  format: yaml
  label: Leapsome Time Tracking API
  slug: leapsome-time-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leapsome/openapi/leapsome-time-tracking-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022 certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance
  trust_center:
    url: https://trust.leapsome.com/
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
name: Leapsome
provenance_date: '2026-11-09'
provider_name: Leapsome
provider_slug: leapsome
slug: leapsome-compliance
source_date: '2026-11-09'
source_filename: leapsome-compliance.yml
source_heading: Compliance
source_page: https://trust.leapsome.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Leapsome\naid: leapsome\nurl: https://trust.leapsome.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/leapsome-trust-center.yml\ntrust_center:\n  url: https://trust.leapsome.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/leapsome/compliance/leapsome-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Leapsome's own page on 2026-11-09.
synthetic: false
tags:
- People Enablement
- Performance Management
- OKRs
- Goals
- Engagement Surveys
- HRIS
- SCIM
- Employee Development
- 1:1 Meetings
- Learning
---
