---
api_specs:
- filename: sigma-ratings-account-api-openapi.yml
  format: yaml
  label: Sigma360 Account API
  slug: sigma-ratings-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-account-api-openapi.yml
- filename: sigma-ratings-informational-api-openapi.yml
  format: yaml
  label: Sigma360 Informational API
  slug: sigma-ratings-informational-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-informational-api-openapi.yml
- filename: sigma-ratings-monitoring-entity-creation-api-openapi.yml
  format: yaml
  label: 'Sigma360 Monitoring: Entity Creation API'
  slug: sigma-ratings-monitoring-entity-creation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-monitoring-entity-creation-api-openapi.yml
- filename: sigma-ratings-monitoring-entity-management-api-openapi.yml
  format: yaml
  label: 'Sigma360 Monitoring: Entity Management API'
  slug: sigma-ratings-monitoring-entity-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-monitoring-entity-management-api-openapi.yml
- filename: sigma-ratings-monitoring-history-api-openapi.yml
  format: yaml
  label: 'Sigma360 Monitoring: History API'
  slug: sigma-ratings-monitoring-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-monitoring-history-api-openapi.yml
- filename: sigma-ratings-one-off-screening-api-openapi.yml
  format: yaml
  label: Sigma360 One-Off Screening API
  slug: sigma-ratings-one-off-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-one-off-screening-api-openapi.yml
- filename: sigma-ratings-utilities-api-openapi.yml
  format: yaml
  label: Sigma360 Utilities API
  slug: sigma-ratings-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-utilities-api-openapi.yml
- filename: sigma-ratings-webhooks-api-openapi.yml
  format: yaml
  label: Sigma360 Webhooks API
  slug: sigma-ratings-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sigma-ratings/openapi/sigma-ratings-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 ISO 27001:2022
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certificate
    type: ISO 27001 certificate
  trust_center:
    url: https://trust.sigma360.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sigma360
provenance_date: '2026-11-10'
provider_name: Sigma360
provider_slug: sigma-ratings
slug: sigma-ratings-compliance
source_date: '2026-11-10'
source_filename: sigma-ratings-compliance.yml
source_heading: Compliance
source_page: https://trust.sigma360.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sigma360\naid: sigma-ratings\nurl: https://trust.sigma360.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.sigma360.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 ISO 27001:2022\n- framework: ISO27001\n  type: ISO 27001 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certificate\n"
source_yaml_url: https://artifacts.apis.io/sigma-ratings/compliance/sigma-ratings-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Sigma360's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- Financial Crime
- KYC
- AML
- Sanctions Screening
- Risk Intelligence
- RegTech
- Adverse Media
---
