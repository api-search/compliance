---
api_specs:
- filename: greptile-query-api-openapi.yml
  format: yaml
  label: Greptile Query API
  slug: greptile-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greptile/openapi/greptile-query-api-openapi.yml
- filename: greptile-repositories-api-openapi.yml
  format: yaml
  label: Greptile Repositories API
  slug: greptile-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greptile/openapi/greptile-repositories-api-openapi.yml
- filename: greptile-search-api-openapi.yml
  format: yaml
  label: Greptile Search API
  slug: greptile-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greptile/openapi/greptile-search-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: unstated
    text: Request our SOC 2 Type II report, bridge letter, and latest penetration test report from the Trust Center .
    type: SOC 2 Type II
  trust_center:
    url: https://www.greptile.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Greptile
provenance_date: '2026-11-09'
provider_name: Greptile
provider_slug: greptile
slug: greptile-compliance
source_date: '2026-11-09'
source_filename: greptile-compliance.yml
source_heading: Compliance
source_page: https://www.greptile.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Greptile\naid: greptile\nurl: https://www.greptile.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/greptile-trust-center.yml\ntrust_center:\n  url: https://www.greptile.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request our SOC 2 Type II report, bridge letter, and latest penetration test report from the Trust Center\n    .\n"
source_yaml_url: https://artifacts.apis.io/greptile/compliance/greptile-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Greptile's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Codebase Understanding
- Code Review
- Code Search
- Developer Tools
---
