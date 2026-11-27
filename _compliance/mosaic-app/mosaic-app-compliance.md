---
api_specs:
- filename: mosaic-app-members-api-openapi.yml
  format: yaml
  label: Mosaic Members API
  slug: mosaic-app-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mosaic-app/openapi/mosaic-app-members-api-openapi.yml
- filename: mosaic-app-projects-api-openapi.yml
  format: yaml
  label: Mosaic Projects API
  slug: mosaic-app-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mosaic-app/openapi/mosaic-app-projects-api-openapi.yml
- filename: mosaic-app-tasks-api-openapi.yml
  format: yaml
  label: Mosaic Tasks API
  slug: mosaic-app-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mosaic-app/openapi/mosaic-app-tasks-api-openapi.yml
- filename: mosaic-app-time-entries-api-openapi.yml
  format: yaml
  label: Mosaic Time Entries API
  slug: mosaic-app-time-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mosaic-app/openapi/mosaic-app-time-entries-api-openapi.yml
- filename: mosaic-app-work-plans-api-openapi.yml
  format: yaml
  label: Mosaic Work Plans API
  slug: mosaic-app-work-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mosaic-app/openapi/mosaic-app-work-plans-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent CPA firm
    period: covering a twelve-month observation period
    report_access: unstated
    scope: null
    text: Mosaic completes a SOC 2 Type II examination every year through an independent CPA firm, covering a twelve-month observation period.
    type: SOC 2 Type II examination
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Mosaic processes customer data as a processor under the GDPR.
    type: processor under GDPR
  trust_center:
    url: https://www.mosaicapp.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mosaic
provenance_date: '2026-11-10'
provider_name: Mosaic
provider_slug: mosaic-app
slug: mosaic-app-compliance
source_date: '2026-11-10'
source_filename: mosaic-app-compliance.yml
source_heading: Compliance
source_page: https://www.mosaicapp.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mosaic\naid: mosaic-app\nurl: https://www.mosaicapp.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mosaic-app-trust-center.yml\ntrust_center:\n  url: https://www.mosaicapp.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: null\n  period: covering a twelve-month observation period\n  issuer: independent CPA firm\n  report_access: unstated\n  text: Mosaic completes a SOC 2 Type II examination every year through an independent CPA firm, covering a twelve-month\n    observation period.\n- framework: GDPR\n  type: processor under GDPR\n  scope: null\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Mosaic processes customer data as a processor under the GDPR.\n"
source_yaml_url: https://artifacts.apis.io/mosaic-app/compliance/mosaic-app-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Mosaic's own page on 2026-11-10.
synthetic: false
tags:
- Resource Management
- Workforce Planning
- Project Management
- AEC
- Professional Services
- Time Tracking
- Forecasting
- AI Assistant
- Integration Platform
- Fortune 500
---
