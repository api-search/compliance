---
api_specs:
- filename: docontrol-authentication-api-openapi.yml
  format: yaml
  label: DoControl Authentication API
  slug: docontrol-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docontrol/openapi/docontrol-authentication-api-openapi.yml
- filename: docontrol-graph-ql-api-openapi.yml
  format: yaml
  label: DoControl Graph QL API
  slug: docontrol-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docontrol/openapi/docontrol-graph-ql-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance certifications (ISO 27001, SOC2 type II)
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance certifications (ISO 27001, SOC2 type II)
    type: Type II
  trust_center:
    url: https://docs.docontrol.io/docontrol-user-guide/getting-started/overview/security-privacy-and-compliance.md
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DoControl
provenance_date: '2026-11-09'
provider_name: DoControl
provider_slug: docontrol
slug: docontrol-compliance
source_date: '2026-11-09'
source_filename: docontrol-compliance.yml
source_heading: Compliance
source_page: https://docs.docontrol.io/docontrol-user-guide/getting-started/overview/security-privacy-and-compliance.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DoControl\naid: docontrol\nurl: https://docs.docontrol.io/docontrol-user-guide/getting-started/overview/security-privacy-and-compliance.md\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/docontrol-trust-center.yml\ntrust_center:\n  url: https://docs.docontrol.io/docontrol-user-guide/getting-started/overview/security-privacy-and-compliance.md\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance certifications (ISO 27001, SOC2 type II)\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Compliance certifications (ISO 27001, SOC2 type II)\n"
source_yaml_url: https://artifacts.apis.io/docontrol/compliance/docontrol-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from DoControl's own page on 2026-11-09.
synthetic: false
tags:
- Data Security
- SaaS Security
- Data Access Governance
- Data Loss Prevention
- Insider Risk Management
- SSPM
- GraphQL
- MCP
---
