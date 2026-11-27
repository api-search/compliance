---
api_specs:
- filename: duck-creek-billing-api-openapi.yml
  format: yaml
  label: Duck Creek Billing API
  slug: duck-creek-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-billing-api-openapi.yml
- filename: duck-creek-claims-api-openapi.yml
  format: yaml
  label: Duck Creek Claims API
  slug: duck-creek-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-claims-api-openapi.yml
- filename: duck-creek-policies-api-openapi.yml
  format: yaml
  label: duck-creek Policies API
  slug: duck-creek-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-policies-api-openapi.yml
- filename: duck-creek-products-api-openapi.yml
  format: yaml
  label: duck-creek Products API
  slug: duck-creek-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-products-api-openapi.yml
- filename: duck-creek-quotes-api-openapi.yml
  format: yaml
  label: duck-creek Quotes API
  slug: duck-creek-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duck-creek/openapi/duck-creek-quotes-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Duck Creek OnDemand information security management system
    text: Duck Creek OnDemand maintains an ISO 27001-certified information security management system
    type: certification
  - framework: SOC1
    issuer: null
    period: annual
    report_access: on_request
    scope: Duck Creek OnDemand
    text: undergoes annual independent SOC 1 Type II and SOC 2 Type II examinations
    type: SOC 1 Type II examination
  - framework: SOC2
    issuer: null
    period: annual
    report_access: on_request
    scope: Duck Creek OnDemand
    text: undergoes annual independent SOC 1 Type II and SOC 2 Type II examinations
    type: SOC 2 Type II examination
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: Duck Creek Embedded Payments
    text: PCI DSS requirements apply specifically where customers use Duck Creek Embedded Payments
    type: SAQ-D SP
  trust_center:
    url: https://www.duckcreek.com/security-and-trust/
frameworks:
- ISO27001
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Duck Creek
provenance_date: '2026-11-09'
provider_name: Duck Creek
provider_slug: duck-creek
slug: duck-creek-compliance
source_date: '2026-11-09'
source_filename: duck-creek-compliance.yml
source_heading: Compliance
source_page: https://www.duckcreek.com/security-and-trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Duck Creek\naid: duck-creek\nurl: https://www.duckcreek.com/security-and-trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/duck-creek-trust-center.yml\ntrust_center:\n  url: https://www.duckcreek.com/security-and-trust/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Duck Creek OnDemand information security management system\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Duck Creek OnDemand maintains an ISO 27001-certified information security management system\n- framework: SOC1\n  type: SOC 1 Type II examination\n  scope: Duck Creek OnDemand\n  period:\
  \ annual\n  issuer: null\n  report_access: on_request\n  text: undergoes annual independent SOC 1 Type II and SOC 2 Type II examinations\n- framework: SOC2\n  type: SOC 2 Type II examination\n  scope: Duck Creek OnDemand\n  period: annual\n  issuer: null\n  report_access: on_request\n  text: undergoes annual independent SOC 1 Type II and SOC 2 Type II examinations\n- framework: PCI-DSS\n  type: SAQ-D SP\n  scope: Duck Creek Embedded Payments\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI DSS requirements apply specifically where customers use Duck Creek Embedded Payments\n"
source_yaml_url: https://artifacts.apis.io/duck-creek/compliance/duck-creek-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Duck Creek's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Payments
- Claims
- Payment Processing
- Product
---
