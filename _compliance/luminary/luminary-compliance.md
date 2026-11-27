---
api_specs:
- filename: luminary-documents-api-openapi.yml
  format: yaml
  label: Luminary Documents API
  slug: luminary-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-documents-api-openapi.yml
- filename: luminary-entities-api-openapi.yml
  format: yaml
  label: Luminary Entities API
  slug: luminary-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-entities-api-openapi.yml
- filename: luminary-households-api-openapi.yml
  format: yaml
  label: Luminary Households API
  slug: luminary-households-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-households-api-openapi.yml
- filename: luminary-individuals-api-openapi.yml
  format: yaml
  label: Luminary Individuals API
  slug: luminary-individuals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-individuals-api-openapi.yml
- filename: luminary-users-api-openapi.yml
  format: yaml
  label: Luminary Users API
  slug: luminary-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-users-api-openapi.yml
- filename: luminary-valuations-api-openapi.yml
  format: yaml
  label: Luminary Valuations API
  slug: luminary-valuations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-valuations-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Luminary platform security and confidentiality controls
    text: to request access to our annual SOC 2 Type II report and more
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    source: https://withluminary.com/security
    text: To learn more about Luminary's security & confidentiality policies, visit our Trust Center to request access to our annual SOC 2 Type II report and more.
    type: SOC 2 Type 2 report
  trust_center:
    url: https://withluminary.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Luminary
provenance_date: '2026-11-10'
provider_name: Luminary
provider_slug: luminary
slug: luminary-compliance
source_date: '2026-11-10'
source_filename: luminary-compliance.yml
source_heading: Compliance
source_page: https://withluminary.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Luminary\naid: luminary\nurl: https://withluminary.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/luminary-trust-center.yml\n  sources:\n  - https://withluminary.com/security\ntrust_center:\n  url: https://withluminary.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Luminary platform security and confidentiality controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: to request access to our annual SOC 2 Type II report and more\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n \
  \ report_access: on_request\n  text: To learn more about Luminary's security & confidentiality policies, visit our Trust Center to request access\n    to our annual SOC 2 Type II report and more.\n  source: https://withluminary.com/security\n"
source_yaml_url: https://artifacts.apis.io/luminary/compliance/luminary-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Luminary's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Estate Planning
- Wealth Management
- Financial Services
- Legal Tech
- Document AI
- Family Office
- OAuth
- Authentication
---
