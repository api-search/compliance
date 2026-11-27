---
api_specs:
- filename: shovels-addresses-api-openapi.yml
  format: yaml
  label: Shovels Addresses API
  slug: shovels-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shovels/openapi/shovels-addresses-api-openapi.yml
- filename: shovels-contractors-api-openapi.yml
  format: yaml
  label: Shovels Contractors API
  slug: shovels-contractors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shovels/openapi/shovels-contractors-api-openapi.yml
- filename: shovels-geography-api-openapi.yml
  format: yaml
  label: Shovels Geography API
  slug: shovels-geography-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shovels/openapi/shovels-geography-api-openapi.yml
- filename: shovels-lists-api-openapi.yml
  format: yaml
  label: Shovels Lists API
  slug: shovels-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shovels/openapi/shovels-lists-api-openapi.yml
- filename: shovels-meta-api-openapi.yml
  format: yaml
  label: Shovels Meta API
  slug: shovels-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shovels/openapi/shovels-meta-api-openapi.yml
- filename: shovels-permits-api-openapi.yml
  format: yaml
  label: Shovels Permits API
  slug: shovels-permits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shovels/openapi/shovels-permits-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Zero Day CPA, PC
    period: null
    report_access: nda
    scope: Security criteria (Common Criteria)
    text: Shovels has completed a SOC 2 Type 2 examination conducted by Zero Day CPA, PC, an independent CPA firm.
    type: SOC 2 Type 2 examination
  trust_center:
    url: https://trust.shovels.ai/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Shovels
provenance_date: '2026-11-10'
provider_name: Shovels
provider_slug: shovels
slug: shovels-compliance
source_date: '2026-11-10'
source_filename: shovels-compliance.yml
source_heading: Compliance
source_page: https://trust.shovels.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Shovels\naid: shovels\nurl: https://trust.shovels.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/shovels-trust-center.yml\ntrust_center:\n  url: https://trust.shovels.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 examination\n  scope: Security criteria (Common Criteria)\n  period: null\n  issuer: Zero Day CPA, PC\n  report_access: nda\n  text: Shovels has completed a SOC 2 Type 2 examination conducted by Zero Day CPA, PC, an independent CPA firm.\n"
source_yaml_url: https://artifacts.apis.io/shovels/compliance/shovels-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Shovels's own page on 2026-11-10.
synthetic: false
tags:
- Construction
- Building Permits
- Contractors
- Real Estate
- Property Data
- Market Intelligence
---
