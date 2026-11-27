---
api_specs:
- filename: logrocket-data-export-api-openapi.yml
  format: yaml
  label: LogRocket Data Export API
  slug: logrocket-data-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logrocket/openapi/logrocket-data-export-api-openapi.yml
- filename: logrocket-highlights-api-openapi.yml
  format: yaml
  label: LogRocket Highlights API
  slug: logrocket-highlights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logrocket/openapi/logrocket-highlights-api-openapi.yml
- filename: logrocket-users-api-openapi.yml
  format: yaml
  label: LogRocket Users API
  slug: logrocket-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logrocket/openapi/logrocket-users-api-openapi.yml
- filename: logrocket-graph-ql-api-openapi.yml
  format: yaml
  label: LogRocket Graph QL API
  slug: logrocket-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logrocket/openapi/logrocket-graph-ql-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: sensitive artifacts — full SOC 2, pen test results, BCDR — are released to a verified work email.
    type: SOC 2 Type II
  trust_center:
    url: https://cpq.logrocket.com/trust
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LogRocket
provenance_date: '2026-11-09'
provider_name: LogRocket
provider_slug: logrocket
slug: logrocket-compliance
source_date: '2026-11-09'
source_filename: logrocket-compliance.yml
source_heading: Compliance
source_page: https://cpq.logrocket.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LogRocket\naid: logrocket\nurl: https://cpq.logrocket.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/logrocket-trust-center.yml\ntrust_center:\n  url: https://cpq.logrocket.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: sensitive artifacts — full SOC 2, pen test results, BCDR — are released to a verified work email.\n"
source_yaml_url: https://artifacts.apis.io/logrocket/compliance/logrocket-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from LogRocket's own page on 2026-11-09.
synthetic: false
tags:
- Session Replay
- Product Analytics
- Frontend Monitoring
- Logging
- Errors
---
