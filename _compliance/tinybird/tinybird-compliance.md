---
api_specs:
- filename: tinybird-analyze-api-openapi.yml
  format: yaml
  label: Tinybird Analyze API
  slug: tinybird-analyze-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-analyze-api-openapi.yml
- filename: tinybird-data-sources-api-openapi.yml
  format: yaml
  label: Tinybird Data Sources API
  slug: tinybird-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-data-sources-api-openapi.yml
- filename: tinybird-environment-variables-api-openapi.yml
  format: yaml
  label: Tinybird Environment Variables API
  slug: tinybird-environment-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-environment-variables-api-openapi.yml
- filename: tinybird-events-api-openapi.yml
  format: yaml
  label: Tinybird Events API
  slug: tinybird-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-events-api-openapi.yml
- filename: tinybird-jobs-api-openapi.yml
  format: yaml
  label: Tinybird Jobs API
  slug: tinybird-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-jobs-api-openapi.yml
- filename: tinybird-organizations-api-openapi.yml
  format: yaml
  label: Tinybird Organizations API
  slug: tinybird-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-organizations-api-openapi.yml
- filename: tinybird-pipes-api-openapi.yml
  format: yaml
  label: Tinybird Pipes API
  slug: tinybird-pipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-pipes-api-openapi.yml
- filename: tinybird-query-api-openapi.yml
  format: yaml
  label: Tinybird Query API
  slug: tinybird-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-query-api-openapi.yml
- filename: tinybird-sink-pipes-api-openapi.yml
  format: yaml
  label: Tinybird Sink Pipes API
  slug: tinybird-sink-pipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-sink-pipes-api-openapi.yml
- filename: tinybird-tokens-api-openapi.yml
  format: yaml
  label: Tinybird Tokens API
  slug: tinybird-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinybird/openapi/tinybird-tokens-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Tinybird is SOC 2 Type II compliant.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Tinybird fully complies with GDPR regulations, with all related requests handled via our support.
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our HIPAA compliance report is available to all customers.
    type: compliance report
  trust_center:
    url: https://www.tinybird.co/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tinybird
provenance_date: '2026-11-10'
provider_name: Tinybird
provider_slug: tinybird
slug: tinybird-compliance
source_date: '2026-11-10'
source_filename: tinybird-compliance.yml
source_heading: Compliance
source_page: https://www.tinybird.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tinybird\naid: tinybird\nurl: https://www.tinybird.co/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tinybird-trust-center.yml\ntrust_center:\n  url: https://www.tinybird.co/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Tinybird is SOC 2 Type II compliant.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Tinybird fully complies with GDPR regulations, with all related requests handled via our support.\n- framework:\
  \ HIPAA\n  type: compliance report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our HIPAA compliance report is available to all customers.\n"
source_yaml_url: https://artifacts.apis.io/tinybird/compliance/tinybird-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Tinybird's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Data
- Real-Time
- SQL
- Streaming
---
