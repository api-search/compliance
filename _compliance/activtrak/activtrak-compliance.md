---
api_specs:
- filename: activtrak-administration-api-openapi.yml
  format: yaml
  label: ActivTrak Administration API
  slug: activtrak-administration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-administration-api-openapi.yml
- filename: activtrak-administration-scim-api-openapi.yml
  format: yaml
  label: ActivTrak Administration - SCIM API
  slug: activtrak-administration-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-administration-scim-api-openapi.yml
- filename: activtrak-bulk-import-api-openapi.yml
  format: yaml
  label: ActivTrak Bulk Import API
  slug: activtrak-bulk-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-bulk-import-api-openapi.yml
- filename: activtrak-reports-api-openapi.yml
  format: yaml
  label: ActivTrak Reports API
  slug: activtrak-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-reports-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Reinforced data protection backed by SOC 2 Type 1 & 2 certifications and end-to-end data encryption.
    type: SOC 2 Type 1 and Type 2
  trust_center:
    url: https://www.activtrak.com/security/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ActivTrak
provenance_date: '2026-11-09'
provider_name: ActivTrak
provider_slug: activtrak
slug: activtrak-compliance
source_date: '2026-11-09'
source_filename: activtrak-compliance.yml
source_heading: Compliance
source_page: https://www.activtrak.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ActivTrak\naid: activtrak\nurl: https://www.activtrak.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/activtrak-trust-center.yml\ntrust_center:\n  url: https://www.activtrak.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 1 and Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Reinforced data protection backed by SOC 2 Type 1 & 2 certifications and end-to-end data encryption.\n"
source_yaml_url: https://artifacts.apis.io/activtrak/compliance/activtrak-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from ActivTrak's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Workforce Analytics
- Productivity
- Employee Monitoring
- Workforce Management
- SCIM
- Reporting
---
