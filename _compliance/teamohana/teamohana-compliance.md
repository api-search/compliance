---
api_specs:
- filename: teamohana-discovery-api-openapi.yml
  format: yaml
  label: TeamOhana Discovery API
  slug: teamohana-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-discovery-api-openapi.yml
- filename: teamohana-headcount-api-openapi.yml
  format: yaml
  label: TeamOhana Headcount API
  slug: teamohana-headcount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-headcount-api-openapi.yml
- filename: teamohana-scenario-api-openapi.yml
  format: yaml
  label: TeamOhana Scenario API
  slug: teamohana-scenario-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-scenario-api-openapi.yml
- filename: teamohana-scim-api-openapi.yml
  format: yaml
  label: TeamOhana SCIM API
  slug: teamohana-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-scim-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Compliant
    type: Compliant
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: Compliant
  trust_center:
    url: https://trust.teamohana.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TeamOhana
provenance_date: '2026-11-10'
provider_name: TeamOhana
provider_slug: teamohana
slug: teamohana-compliance
source_date: '2026-11-10'
source_filename: teamohana-compliance.yml
source_heading: Compliance
source_page: https://trust.teamohana.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TeamOhana\naid: teamohana\nurl: https://trust.teamohana.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.teamohana.com/\nattestations:\n- framework: ISO27001\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Compliant\n- framework: SOC2\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/teamohana/compliance/teamohana-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from TeamOhana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Human Resources
- Headcount Management
- Headcount Planning
- Workforce Planning
- Talent Acquisition
- Finance
- SCIM
- Software-as-a-Service
---
