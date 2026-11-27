---
api_specs:
- filename: replit-deployments-api-openapi.yml
  format: yaml
  label: Replit Deployments API
  slug: replit-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-deployments-api-openapi.yml
- filename: replit-repls-api-openapi.yml
  format: yaml
  label: Replit Repls API
  slug: replit-repls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-repls-api-openapi.yml
- filename: replit-users-api-openapi.yml
  format: yaml
  label: Replit Users API
  slug: replit-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent CPA firm
    period: annually
    report_access: on_request
    scope: Replit platform
    text: Replit is SOC 2 Type II audited annually by an independent CPA firm
    type: SOC 2 Type II audit
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: infrastructure
    text: GCP ISO 27001 Cert (infra assurance)
    type: GCP ISO 27001 certificate (infrastructure assurance)
  trust_center:
    url: https://trust.replit.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Replit
provenance_date: '2026-11-10'
provider_name: Replit
provider_slug: replit
slug: replit-compliance
source_date: '2026-11-10'
source_filename: replit-compliance.yml
source_heading: Compliance
source_page: https://trust.replit.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Replit\naid: replit\nurl: https://trust.replit.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/replit-trust-center.yml\ntrust_center:\n  url: https://trust.replit.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Replit platform\n  period: annually\n  issuer: independent CPA firm\n  report_access: on_request\n  text: Replit is SOC 2 Type II audited annually by an independent CPA firm\n- framework: ISO27001\n  type: GCP ISO 27001 certificate (infrastructure assurance)\n  scope: infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GCP ISO\
  \ 27001 Cert (infra assurance)\n"
source_yaml_url: https://artifacts.apis.io/replit/compliance/replit-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Replit's own page on 2026-11-10.
synthetic: false
tags:
- Code
- Compiling
- Developer Tools
- Development Environment
- Programming Language
- Version Control
---
