---
api_specs:
- filename: cumulio-authorize-api-openapi.yml
  format: yaml
  label: Cumulio Authorize API
  slug: cumulio-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-authorize-api-openapi.yml
- filename: cumulio-datasets-api-openapi.yml
  format: yaml
  label: Cumulio Datasets API
  slug: cumulio-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-datasets-api-openapi.yml
- filename: cumulio-exchange-api-openapi.yml
  format: yaml
  label: Cumulio Exchange API
  slug: cumulio-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-exchange-api-openapi.yml
- filename: cumulio-query-api-openapi.yml
  format: yaml
  label: Cumulio Query API
  slug: cumulio-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-query-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: Jan 1st, 2025 until Dec 31st, 2025
    report_access: on_request
    scope: null
    text: SOC2 Type 2 Report for the reporting period of Jan 1st, 2025 until Dec 31st, 2025
    type: Type 2
  - framework: SOC2
    issuer: null
    period: Jan 1st, 2024 until Dec 31st, 2024
    report_access: on_request
    scope: null
    text: SOC2 Type 2 Report for the reporting period of Jan 1st, 2024 until Dec 31st, 2024
    type: Type 2
  - framework: SOC2
    issuer: null
    period: since Jan 1st 2026
    report_access: on_request
    scope: null
    text: Bridge letter for the period since Jan 1st 2026
    type: Bridge letter
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes, Luzmo is fully GDPR compliant.
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes, Luzmo is compliant with HIPAA (Health...) regulations.
    type: compliance statement; BAA available on request
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Luzmo is compliant with the NIS2 directive.
    type: NIS2 directive compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Luzmo is compliant with the EU AI Act.
    type: EU AI Act compliance statement
  trust_center:
    url: https://trust.luzmo.com/
frameworks:
- GDPR
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Cumulio
provenance_date: '2026-11-09'
provider_name: Cumulio
provider_slug: cumulio
slug: cumulio-compliance
source_date: '2026-11-09'
source_filename: cumulio-compliance.yml
source_heading: Compliance
source_page: https://trust.luzmo.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Cumulio\naid: cumulio\nurl: https://trust.luzmo.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.luzmo.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: Jan 1st, 2025 until Dec 31st, 2025\n  issuer: null\n  report_access: on_request\n  text: SOC2 Type 2 Report for the reporting period of Jan 1st, 2025 until Dec 31st, 2025\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: Jan 1st, 2024 until Dec 31st, 2024\n  issuer: null\n  report_access: on_request\n  text: SOC2 Type 2 Report for the reporting period of Jan 1st, 2024 until Dec 31st, 2024\n- framework:\
  \ SOC2\n  type: Bridge letter\n  scope: null\n  period: since Jan 1st 2026\n  issuer: null\n  report_access: on_request\n  text: Bridge letter for the period since Jan 1st 2026\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, Luzmo is fully GDPR compliant.\n- framework: HIPAA\n  type: compliance statement; BAA available on request\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes, Luzmo is compliant with HIPAA (Health...) regulations.\n- framework: other\n  type: NIS2 directive compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Luzmo is compliant with the NIS2 directive.\n- framework: other\n  type: EU AI Act compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Luzmo is compliant with the EU AI Act.\n"
source_yaml_url: https://artifacts.apis.io/cumulio/compliance/cumulio-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Cumulio's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
