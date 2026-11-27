---
api_specs:
- filename: termius-group-api-openapi.yml
  format: yaml
  label: Termius Group API
  slug: termius-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/termius/openapi/termius-group-api-openapi.yml
- filename: termius-host-api-openapi.yml
  format: yaml
  label: Termius Host API
  slug: termius-host-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/termius/openapi/termius-host-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: Termius 2025 Type II SOC 2.pdf
    type: Type II
  trust_center:
    url: https://security.termius.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Termius
provenance_date: '2026-11-10'
provider_name: Termius
provider_slug: termius
slug: termius-compliance
source_date: '2026-11-10'
source_filename: termius-compliance.yml
source_heading: Compliance
source_page: https://security.termius.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Termius\naid: termius\nurl: https://security.termius.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://security.termius.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: Termius 2025 Type II SOC 2.pdf\n"
source_yaml_url: https://artifacts.apis.io/termius/compliance/termius-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Termius's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- SSH
- SSH Client
- Terminal
- Developer Tools
- DevOps
- Infrastructure
- Security
- Remote Access
---
