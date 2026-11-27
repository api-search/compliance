---
api_specs:
- filename: cherre-auth-api-openapi.yml
  format: yaml
  label: Cherre Auth API
  slug: cherre-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherre/openapi/cherre-auth-api-openapi.yml
- filename: cherre-graph-ql-api-openapi.yml
  format: yaml
  label: Cherre Graph QL API
  slug: cherre-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherre/openapi/cherre-graph-ql-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: external examiner (unnamed)
    period: null
    report_access: unstated
    scope: Security and Confidentiality trust service categories
    text: Cherre is proud to have completed the SOC2 Type 2 examination.
    type: SOC 2 Type 2 examination
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security program
    text: Our security framework is based on ISO 27001 and NIST 800-53 Information Security Standards
    type: security framework basis
  trust_center:
    url: https://cherre.com/security/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cherre
provenance_date: '2026-11-09'
provider_name: Cherre
provider_slug: cherre
slug: cherre-compliance
source_date: '2026-11-09'
source_filename: cherre-compliance.yml
source_heading: Compliance
source_page: https://cherre.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cherre\naid: cherre\nurl: https://cherre.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/cherre-trust-center.yml\ntrust_center:\n  url: https://cherre.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: Security and Confidentiality trust service categories\n  period: null\n  issuer: external examiner (unnamed)\n  report_access: unstated\n  text: Cherre is proud to have completed the SOC2 Type 2 examination.\n- framework: ISO27001\n  type: security framework basis\n  scope: Information Security program\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Our security framework is based on ISO 27001 and NIST 800-53 Information Security Standards\n"
source_yaml_url: https://artifacts.apis.io/cherre/compliance/cherre-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Cherre's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Property Intelligence
- Data Integration
- Knowledge Graph
- GraphQL
---
