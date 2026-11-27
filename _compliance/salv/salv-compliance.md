---
api_specs:
- filename: salv-alert-api-openapi.yml
  format: yaml
  label: Salv Alert API
  slug: salv-alert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-alert-api-openapi.yml
- filename: salv-alerts-api-openapi.yml
  format: yaml
  label: Salv Alerts API
  slug: salv-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-alerts-api-openapi.yml
- filename: salv-aml-api-openapi.yml
  format: yaml
  label: Salv Aml API
  slug: salv-aml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-aml-api-openapi.yml
- filename: salv-custom-list-record-api-openapi.yml
  format: yaml
  label: Salv Custom List Record API
  slug: salv-custom-list-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-custom-list-record-api-openapi.yml
- filename: salv-custom-list-usable-field-public-api-openapi.yml
  format: yaml
  label: Salv Custom List Usable Field Public API
  slug: salv-custom-list-usable-field-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-custom-list-usable-field-public-api-openapi.yml
- filename: salv-data-upload-api-openapi.yml
  format: yaml
  label: Salv Data Upload API
  slug: salv-data-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-data-upload-api-openapi.yml
- filename: salv-manual-alerts-api-openapi.yml
  format: yaml
  label: Salv Manual Alerts API
  slug: salv-manual-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-manual-alerts-api-openapi.yml
- filename: salv-monitoring-checks-api-openapi.yml
  format: yaml
  label: Salv Monitoring Checks API
  slug: salv-monitoring-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-monitoring-checks-api-openapi.yml
- filename: salv-note-api-openapi.yml
  format: yaml
  label: Salv Note API
  slug: salv-note-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-note-api-openapi.yml
- filename: salv-risk-api-openapi.yml
  format: yaml
  label: Salv Risk API
  slug: salv-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-risk-api-openapi.yml
- filename: salv-screening-alerts-api-openapi.yml
  format: yaml
  label: Salv Screening Alerts API
  slug: salv-screening-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-screening-alerts-api-openapi.yml
- filename: salv-screening-checks-api-openapi.yml
  format: yaml
  label: Salv Screening Checks API
  slug: salv-screening-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-screening-checks-api-openapi.yml
- filename: salv-screening-list-groups-api-openapi.yml
  format: yaml
  label: Salv Screening List Groups API
  slug: salv-screening-list-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-screening-list-groups-api-openapi.yml
- filename: salv-screening-searches-api-openapi.yml
  format: yaml
  label: Salv Screening Searches API
  slug: salv-screening-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-screening-searches-api-openapi.yml
- filename: salv-unresolved-alerts-api-openapi.yml
  format: yaml
  label: Salv Unresolved Alerts API
  slug: salv-unresolved-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salv/openapi/salv-unresolved-alerts-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'Salv has an ISO/IEC 27001: 2022 certificate'
    type: certificate
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: as well as ISAE 3000 compliant SOC 2 Type 2 report
    type: Type 2 report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2, ISO 27001, DORA, pen tests
    type: listed in trust and security navigation
  trust_center:
    url: https://salv.com/
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Salv
provenance_date: '2026-11-10'
provider_name: Salv
provider_slug: salv
slug: salv-compliance
source_date: '2026-11-10'
source_filename: salv-compliance.yml
source_heading: Compliance
source_page: https://salv.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Salv\naid: salv\nurl: https://salv.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://salv.com/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Salv has an ISO/IEC 27001: 2022 certificate'\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: as well as ISAE 3000 compliant SOC 2 Type 2 report\n- framework: other\n  type: listed in trust and security navigation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: SOC 2, ISO 27001, DORA, pen tests\n"
source_yaml_url: https://artifacts.apis.io/salv/compliance/salv-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Salv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AML
- Financial Crime
- Compliance
- RegTech
- Sanctions Screening
- Transaction Monitoring
- Fraud Prevention
---
