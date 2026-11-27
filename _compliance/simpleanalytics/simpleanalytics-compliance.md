---
api_specs:
- filename: simpleanalytics-events-api-openapi.yml
  format: yaml
  label: Simple Analytics Events API
  slug: simpleanalytics-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-events-api-openapi.yml
- filename: simpleanalytics-export-api-openapi.yml
  format: yaml
  label: Simple Analytics Export API
  slug: simpleanalytics-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-export-api-openapi.yml
- filename: simpleanalytics-stats-api-openapi.yml
  format: yaml
  label: Simple Analytics Stats API
  slug: simpleanalytics-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-stats-api-openapi.yml
- filename: simpleanalytics-websites-api-openapi.yml
  format: yaml
  label: Simple Analytics Websites API
  slug: simpleanalytics-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-websites-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality
    text: We are currently working toward SOC 2 Type II certification. Audit in progress
    type: SOC 2 Type II
  trust_center:
    url: https://www.simpleanalytics.com/gdpr-compliance
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Simple Analytics
provenance_date: '2026-11-10'
provider_name: Simple Analytics
provider_slug: simpleanalytics
slug: simpleanalytics-compliance
source_date: '2026-11-10'
source_filename: simpleanalytics-compliance.yml
source_heading: Compliance
source_page: https://www.simpleanalytics.com/gdpr-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Simple Analytics\naid: simpleanalytics\nurl: https://www.simpleanalytics.com/gdpr-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.simpleanalytics.com/gdpr-compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We are currently working toward SOC 2 Type II certification. Audit in progress\n"
source_yaml_url: https://artifacts.apis.io/simpleanalytics/compliance/simpleanalytics-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Simple Analytics's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Privacy
- Cookieless
- GDPR
- Event
- Data Export
- Europe
---
