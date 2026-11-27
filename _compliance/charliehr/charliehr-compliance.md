---
api_specs:
- filename: charliehr-company-api-openapi.yml
  format: yaml
  label: CharlieHR Company API
  slug: charliehr-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charliehr/openapi/charliehr-company-api-openapi.yml
- filename: charliehr-leave-absences-api-openapi.yml
  format: yaml
  label: CharlieHR Leave / Absences API
  slug: charliehr-leave-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charliehr/openapi/charliehr-leave-absences-api-openapi.yml
- filename: charliehr-leave-allowances-api-openapi.yml
  format: yaml
  label: CharlieHR Leave Allowances API
  slug: charliehr-leave-allowances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charliehr/openapi/charliehr-leave-allowances-api-openapi.yml
- filename: charliehr-team-members-api-openapi.yml
  format: yaml
  label: CharlieHR Team Members API
  slug: charliehr-team-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charliehr/openapi/charliehr-team-members-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: Charlie is fully GDPR-compliant and ISO 27001-certified
    type: certification
  - framework: GDPR
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: Charlie is fully GDPR-compliant and ISO 27001-certified
    type: compliance claim
  trust_center:
    url: https://www.charliehr.com/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CharlieHR
provenance_date: '2026-11-09'
provider_name: CharlieHR
provider_slug: charliehr
slug: charliehr-compliance
source_date: '2026-11-09'
source_filename: charliehr-compliance.yml
source_heading: Compliance
source_page: https://www.charliehr.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CharlieHR\naid: charliehr\nurl: https://www.charliehr.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/charliehr-trust-center.yml\ntrust_center:\n  url: https://www.charliehr.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: Charlie is fully GDPR-compliant and ISO 27001-certified\n- framework: GDPR\n  type: compliance claim\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: Charlie is fully GDPR-compliant and ISO 27001-certified\n"
source_yaml_url: https://artifacts.apis.io/charliehr/compliance/charliehr-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from CharlieHR's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- HRIS
- People
- Leave
- Time Off
---
