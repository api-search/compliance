---
api_specs:
- filename: harvest-clients-api-openapi.yml
  format: yaml
  label: Harvest Clients API
  slug: harvest-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-clients-api-openapi.yml
- filename: harvest-company-api-openapi.yml
  format: yaml
  label: Harvest Company API
  slug: harvest-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-company-api-openapi.yml
- filename: harvest-estimates-api-openapi.yml
  format: yaml
  label: Harvest Estimates API
  slug: harvest-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-estimates-api-openapi.yml
- filename: harvest-expenses-api-openapi.yml
  format: yaml
  label: Harvest Expenses API
  slug: harvest-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-expenses-api-openapi.yml
- filename: harvest-invoices-api-openapi.yml
  format: yaml
  label: Harvest Invoices API
  slug: harvest-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-invoices-api-openapi.yml
- filename: harvest-projects-api-openapi.yml
  format: yaml
  label: Harvest Projects API
  slug: harvest-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-projects-api-openapi.yml
- filename: harvest-reports-api-openapi.yml
  format: yaml
  label: Harvest Reports API
  slug: harvest-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-reports-api-openapi.yml
- filename: harvest-roles-api-openapi.yml
  format: yaml
  label: Harvest Roles API
  slug: harvest-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-roles-api-openapi.yml
- filename: harvest-tasks-api-openapi.yml
  format: yaml
  label: Harvest Tasks API
  slug: harvest-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-tasks-api-openapi.yml
- filename: harvest-users-api-openapi.yml
  format: yaml
  label: Harvest Users API
  slug: harvest-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-users-api-openapi.yml
- filename: harvest-time-entries-api-openapi.yml
  format: yaml
  label: Harvest Time Entries API
  slug: harvest-time-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harvest/openapi/harvest-time-entries-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Harvest has a PCI-DSS Merchant Certificate, although we don’t store any payment information.
    type: Merchant Certificate
  trust_center:
    url: https://www.getharvest.com/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Harvest
provenance_date: '2026-11-09'
provider_name: Harvest
provider_slug: harvest
slug: harvest-compliance
source_date: '2026-11-09'
source_filename: harvest-compliance.yml
source_heading: Compliance
source_page: https://www.getharvest.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Harvest\naid: harvest\nurl: https://www.getharvest.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/harvest-trust-center.yml\ntrust_center:\n  url: https://www.getharvest.com/security\nattestations:\n- framework: PCI-DSS\n  type: Merchant Certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Harvest has a PCI-DSS Merchant Certificate, although we don’t store any payment information.\n"
source_yaml_url: https://artifacts.apis.io/harvest/compliance/harvest-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Harvest's own page on 2026-11-09.
synthetic: false
tags:
- Time Tracking
- Project Management
- Invoicing
- Expense Tracking
- Timesheets
- Professional Services
- Harvest
---
