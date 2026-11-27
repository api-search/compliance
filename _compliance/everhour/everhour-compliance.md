---
api_specs:
- filename: everhour-clients-api-openapi.yml
  format: yaml
  label: Everhour Clients API
  slug: everhour-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-clients-api-openapi.yml
- filename: everhour-expenses-api-openapi.yml
  format: yaml
  label: Everhour Expenses API
  slug: everhour-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-expenses-api-openapi.yml
- filename: everhour-invoices-api-openapi.yml
  format: yaml
  label: Everhour Invoices API
  slug: everhour-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-invoices-api-openapi.yml
- filename: everhour-projects-api-openapi.yml
  format: yaml
  label: Everhour Projects API
  slug: everhour-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-projects-api-openapi.yml
- filename: everhour-reports-api-openapi.yml
  format: yaml
  label: Everhour Reports API
  slug: everhour-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-reports-api-openapi.yml
- filename: everhour-schedule-api-openapi.yml
  format: yaml
  label: Everhour Schedule API
  slug: everhour-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-schedule-api-openapi.yml
- filename: everhour-tasks-api-openapi.yml
  format: yaml
  label: Everhour Tasks API
  slug: everhour-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-tasks-api-openapi.yml
- filename: everhour-time-off-api-openapi.yml
  format: yaml
  label: Everhour Time Off API
  slug: everhour-time-off-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-time-off-api-openapi.yml
- filename: everhour-time-records-api-openapi.yml
  format: yaml
  label: Everhour Time Records API
  slug: everhour-time-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-time-records-api-openapi.yml
- filename: everhour-timecards-api-openapi.yml
  format: yaml
  label: Everhour Timecards API
  slug: everhour-timecards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-timecards-api-openapi.yml
- filename: everhour-timers-api-openapi.yml
  format: yaml
  label: Everhour Timers API
  slug: everhour-timers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-timers-api-openapi.yml
- filename: everhour-timesheets-api-openapi.yml
  format: yaml
  label: Everhour Timesheets API
  slug: everhour-timesheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-timesheets-api-openapi.yml
- filename: everhour-users-api-openapi.yml
  format: yaml
  label: Everhour Users API
  slug: everhour-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-users-api-openapi.yml
- filename: everhour-webhooks-api-openapi.yml
  format: yaml
  label: Everhour Webhooks API
  slug: everhour-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everhour/openapi/everhour-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Everhour has a PCI-DSS Merchant Certificate, although we don’t store any payment information.
    type: Merchant Certificate
  trust_center:
    url: https://everhour.com/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Everhour
provenance_date: '2026-11-09'
provider_name: Everhour
provider_slug: everhour
slug: everhour-compliance
source_date: '2026-11-09'
source_filename: everhour-compliance.yml
source_heading: Compliance
source_page: https://everhour.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Everhour\naid: everhour\nurl: https://everhour.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/everhour-trust-center.yml\ntrust_center:\n  url: https://everhour.com/security\nattestations:\n- framework: PCI-DSS\n  type: Merchant Certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Everhour has a PCI-DSS Merchant Certificate, although we don’t store any payment information.\n"
source_yaml_url: https://artifacts.apis.io/everhour/compliance/everhour-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Everhour's own page on 2026-11-09.
synthetic: false
tags:
- Time Tracking
- Timesheets
- Productivity
- Project Management
- Budgeting
- Invoicing
---
