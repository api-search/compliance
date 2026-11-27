---
api_specs:
- filename: new-relic-alerts-api-openapi.yml
  format: yaml
  label: New Relic Alerts API
  slug: new-relic-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/new-relic/openapi/new-relic-alerts-api-openapi.yml
- filename: new-relic-applications-api-openapi.yml
  format: yaml
  label: New Relic Applications API
  slug: new-relic-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/new-relic/openapi/new-relic-applications-api-openapi.yml
- filename: new-relic-events-api-openapi.yml
  format: yaml
  label: New Relic Events API
  slug: new-relic-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/new-relic/openapi/new-relic-events-api-openapi.yml
- filename: new-relic-get-api-openapi.yml
  format: yaml
  label: New Relic Get API
  slug: new-relic-get-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/new-relic/openapi/new-relic-get-api-openapi.yml
- filename: new-relic-logs-api-openapi.yml
  format: yaml
  label: New Relic Logs API
  slug: new-relic-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/new-relic/openapi/new-relic-logs-api-openapi.yml
- filename: new-relic-metrics-api-openapi.yml
  format: yaml
  label: New Relic Metrics API
  slug: new-relic-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/new-relic/openapi/new-relic-metrics-api-openapi.yml
- filename: new-relic-traces-api-openapi.yml
  format: yaml
  label: New Relic Traces API
  slug: new-relic-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/new-relic/openapi/new-relic-traces-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: New Relic ISO 27001:2022 Certificate.pdf
    type: certificate
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: New Relic ISO 42001:2023 Certificate.pdf
    type: certificate
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: New Relic - 2026 - Type 2 SOC 2 - Summary of Engagement Letter.pdf
    type: Type 2 report summary of engagement letter
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: New Relic SOC 3 Type 2 Report.pdf
    type: Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.newrelic.com/
    text: New Relic ISO 27001:2022 Certificate.pdf
    type: certificate
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.newrelic.com/
    text: New Relic ISO 42001:2023 Certificate.pdf
    type: certificate
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.newrelic.com/
    text: New Relic - 2026 - Type 2 SOC 2 - Summary of Engagement Letter.pdf
    type: Type 2 report summary
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.newrelic.com/
    text: New Relic SOC 3 Type 2 Report.pdf
    type: Type 2 report
  trust_center:
    url: https://trust.newrelic.com/
frameworks:
- ISO27001
- ISO42001
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: New Relic
provenance_date: '2026-11-10'
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-compliance
source_date: '2026-11-10'
source_filename: new-relic-compliance.yml
source_heading: Compliance
source_page: https://trust.newrelic.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: New Relic\naid: new-relic\nurl: https://trust.newrelic.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.newrelic.com/\ntrust_center:\n  url: https://trust.newrelic.com/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: New Relic ISO 27001:2022 Certificate.pdf\n- framework: ISO42001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: New Relic ISO 42001:2023 Certificate.pdf\n- framework: SOC2\n  type: Type 2 report summary of engagement letter\n  scope: null\n\
  \  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: New Relic - 2026 - Type 2 SOC 2 - Summary of Engagement Letter.pdf\n- framework: SOC3\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: New Relic SOC 3 Type 2 Report.pdf\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: New Relic ISO 27001:2022 Certificate.pdf\n  source: https://trust.newrelic.com/\n- framework: ISO42001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: New Relic ISO 42001:2023 Certificate.pdf\n  source: https://trust.newrelic.com/\n- framework: SOC2\n  type: Type 2 report summary\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: New Relic - 2026 - Type 2 SOC 2 - Summary of Engagement Letter.pdf\n  source: https://trust.newrelic.com/\n- framework: SOC3\n  type: Type 2 report\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: New Relic SOC 3 Type 2 Report.pdf\n  source: https://trust.newrelic.com/\n"
source_yaml_url: https://artifacts.apis.io/new-relic/compliance/new-relic-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from New Relic's own page on 2026-11-10.
synthetic: false
tags:
- Analysis
- Analytics
- APM
- DevOps
- Infrastructure
- Monitoring
- Observability
- Performance
- Platform
- Real-Time
---
