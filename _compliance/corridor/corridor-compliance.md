---
api_specs:
- filename: corridor-dashboard-api-openapi.yml
  format: yaml
  label: Corridor Dashboard API
  slug: corridor-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-dashboard-api-openapi.yml
- filename: corridor-findings-api-openapi.yml
  format: yaml
  label: Corridor Findings API
  slug: corridor-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-findings-api-openapi.yml
- filename: corridor-guardrails-api-openapi.yml
  format: yaml
  label: Corridor Guardrails API
  slug: corridor-guardrails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-guardrails-api-openapi.yml
- filename: corridor-pr-reviews-api-openapi.yml
  format: yaml
  label: Corridor PR Reviews API
  slug: corridor-pr-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-pr-reviews-api-openapi.yml
- filename: corridor-projects-api-openapi.yml
  format: yaml
  label: Corridor Projects API
  slug: corridor-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-projects-api-openapi.yml
- filename: corridor-teams-api-openapi.yml
  format: yaml
  label: Corridor Teams API
  slug: corridor-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corridor/openapi/corridor-teams-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Corridor SOC 2 Type I 04.01.26.pdf
    type: Type I
  trust_center:
    url: https://trust.corridor.dev/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Corridor
provenance_date: '2026-11-09'
provider_name: Corridor
provider_slug: corridor
slug: corridor-compliance
source_date: '2026-11-09'
source_filename: corridor-compliance.yml
source_heading: Compliance
source_page: https://trust.corridor.dev/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Corridor\naid: corridor\nurl: https://trust.corridor.dev/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.corridor.dev/\nattestations:\n- framework: SOC2\n  type: Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Corridor SOC 2 Type I 04.01.26.pdf\n"
source_yaml_url: https://artifacts.apis.io/corridor/compliance/corridor-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Corridor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Application Security
- AI Coding
- Code Security
- Developer Tools
- Guardrails
- MCP
- Static Analysis
- DevSecOps
---
