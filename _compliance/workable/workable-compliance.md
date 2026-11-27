---
api_specs:
- filename: workable-accounts-api-openapi.yml
  format: yaml
  label: Workable Accounts API
  slug: workable-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-accounts-api-openapi.yml
- filename: workable-candidates-api-openapi.yml
  format: yaml
  label: Workable Candidates API
  slug: workable-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-candidates-api-openapi.yml
- filename: workable-departments-api-openapi.yml
  format: yaml
  label: Workable Departments API
  slug: workable-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-departments-api-openapi.yml
- filename: workable-employees-api-openapi.yml
  format: yaml
  label: Workable Employees API
  slug: workable-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-employees-api-openapi.yml
- filename: workable-events-api-openapi.yml
  format: yaml
  label: Workable Events API
  slug: workable-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-events-api-openapi.yml
- filename: workable-jobs-api-openapi.yml
  format: yaml
  label: Workable Jobs API
  slug: workable-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-jobs-api-openapi.yml
- filename: workable-members-api-openapi.yml
  format: yaml
  label: Workable Members API
  slug: workable-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-members-api-openapi.yml
- filename: workable-offers-api-openapi.yml
  format: yaml
  label: Workable Offers API
  slug: workable-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-offers-api-openapi.yml
- filename: workable-recruiters-api-openapi.yml
  format: yaml
  label: Workable Recruiters API
  slug: workable-recruiters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-recruiters-api-openapi.yml
- filename: workable-requisitions-api-openapi.yml
  format: yaml
  label: Workable Requisitions API
  slug: workable-requisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-requisitions-api-openapi.yml
- filename: workable-stages-api-openapi.yml
  format: yaml
  label: Workable Stages API
  slug: workable-stages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-stages-api-openapi.yml
- filename: workable-subscriptions-api-openapi.yml
  format: yaml
  label: Workable Subscriptions API
  slug: workable-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-subscriptions-api-openapi.yml
- filename: workable-custom-attributes-api-openapi.yml
  format: yaml
  label: Workable Custom Attributes API
  slug: workable-custom-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-custom-attributes-api-openapi.yml
- filename: workable-review-cycles-api-openapi.yml
  format: yaml
  label: Workable Review Cycles API
  slug: workable-review-cycles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-review-cycles-api-openapi.yml
- filename: workable-time-off-api-openapi.yml
  format: yaml
  label: Workable Time Off API
  slug: workable-time-off-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-time-off-api-openapi.yml
- filename: workable-time-tracking-api-openapi.yml
  format: yaml
  label: Workable Time Tracking API
  slug: workable-time-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workable/openapi/workable-time-tracking-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: Information Security Management System (ISMS)
    text: ISO/IEC 27001 Information Security Management System (ISMS) Download certificate
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: public
    scope: Security Controls for the Provision and Use of Cloud Services
    text: ISO/IEC 27017 Security Controls for the Provision and Use of Cloud Services Download certificate
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Trust Services Principles
    text: SOC 2 (Type II) Trust Services Principles Contact us for access
    type: report
  - framework: SOC3
    issuer: null
    period: null
    report_access: public
    scope: Service organization controls
    text: SOC 3 Service organization controls Download certificate
    type: report
  trust_center:
    url: https://www.workable.com/security
frameworks:
- ISO27001
- ISO27017
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Workable
provenance_date: '2026-11-10'
provider_name: Workable
provider_slug: workable
slug: workable-compliance
source_date: '2026-11-10'
source_filename: workable-compliance.yml
source_heading: Compliance
source_page: https://www.workable.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Workable\naid: workable\nurl: https://www.workable.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/workable-trust-center.yml\ntrust_center:\n  url: https://www.workable.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Information Security Management System (ISMS)\n  period: null\n  issuer: null\n  report_access: public\n  text: ISO/IEC 27001 Information Security Management System (ISMS) Download certificate\n- framework: ISO27017\n  type: certification\n  scope: Security Controls for the Provision and Use of Cloud Services\n  period: null\n  issuer: null\n\
  \  report_access: public\n  text: ISO/IEC 27017 Security Controls for the Provision and Use of Cloud Services Download certificate\n- framework: SOC2\n  type: report\n  scope: Trust Services Principles\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 (Type II) Trust Services Principles Contact us for access\n- framework: SOC3\n  type: report\n  scope: Service organization controls\n  period: null\n  issuer: null\n  report_access: public\n  text: SOC 3 Service organization controls Download certificate\n"
source_yaml_url: https://artifacts.apis.io/workable/compliance/workable-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Workable's own page on 2026-11-10.
synthetic: false
tags:
- Human Resources
- Applicant Tracking
- Recruiting
- Sourcing
- Video Interviews
- Assessment
- Software-as-a-Service
---
