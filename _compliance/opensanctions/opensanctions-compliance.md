---
api_specs:
- filename: opensanctions-data-access-api-openapi.yml
  format: yaml
  label: OpenSanctions Data access API
  slug: opensanctions-data-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-data-access-api-openapi.yml
- filename: opensanctions-matching-api-openapi.yml
  format: yaml
  label: OpenSanctions Matching API
  slug: opensanctions-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-matching-api-openapi.yml
- filename: opensanctions-reconciliation-api-openapi.yml
  format: yaml
  label: OpenSanctions Reconciliation API
  slug: opensanctions-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-reconciliation-api-openapi.yml
- filename: opensanctions-system-information-api-openapi.yml
  format: yaml
  label: OpenSanctions System information API
  slug: opensanctions-system-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-system-information-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: '2024'
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate (2024)
    type: certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  trust_center:
    url: https://trust.opensanctions.org/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OpenSanctions
provenance_date: '2026-11-10'
provider_name: OpenSanctions
provider_slug: opensanctions
slug: opensanctions-compliance
source_date: '2026-11-10'
source_filename: opensanctions-compliance.yml
source_heading: Compliance
source_page: https://trust.opensanctions.org/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OpenSanctions\naid: opensanctions\nurl: https://trust.opensanctions.org/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/opensanctions-trust-center.yml\ntrust_center:\n  url: https://trust.opensanctions.org/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate (2024)\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/opensanctions/compliance/opensanctions-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from OpenSanctions's own page on 2026-11-10.
synthetic: false
tags:
- Sanctions Screening
- AML
- Politically Exposed Persons
- Compliance
- Financial Crime
- KYC
- Entity Resolution
- Open Data
- Risk Data
- Due Diligence
- Public APIs
- Agent-Native
---
