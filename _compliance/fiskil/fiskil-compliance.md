---
api_specs:
- filename: fiskil-auth-api-openapi.yml
  format: yaml
  label: FISKIL Auth API
  slug: fiskil-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-auth-api-openapi.yml
- filename: fiskil-banking-api-openapi.yml
  format: yaml
  label: FISKIL Banking API
  slug: fiskil-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-banking-api-openapi.yml
- filename: fiskil-common-api-openapi.yml
  format: yaml
  label: FISKIL Common API
  slug: fiskil-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-common-api-openapi.yml
- filename: fiskil-consent-api-openapi.yml
  format: yaml
  label: FISKIL Consent API
  slug: fiskil-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-consent-api-openapi.yml
- filename: fiskil-end-users-api-openapi.yml
  format: yaml
  label: FISKIL End users API
  slug: fiskil-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-end-users-api-openapi.yml
- filename: fiskil-energy-api-openapi.yml
  format: yaml
  label: FISKIL Energy API
  slug: fiskil-energy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-energy-api-openapi.yml
- filename: fiskil-institutions-api-openapi.yml
  format: yaml
  label: FISKIL Institutions API
  slug: fiskil-institutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-institutions-api-openapi.yml
- filename: fiskil-transactions-api-openapi.yml
  format: yaml
  label: FISKIL Transactions API
  slug: fiskil-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: on_request
    scope: unstated
    text: Fiskil is compliant with leading industry security standards, including SOC 2 Type 2.
    type: Type II
  - framework: other
    issuer: unstated
    period: null
    report_access: on_request
    scope: unstated
    text: ASAE 3150 Type II Processes in place to manage risk and secure systems.
    type: ASAE 3150 Type II
  trust_center:
    url: https://www.fiskil.com/security
frameworks:
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: FISKIL
provenance_date: '2026-11-09'
provider_name: FISKIL
provider_slug: fiskil
slug: fiskil-compliance
source_date: '2026-11-09'
source_filename: fiskil-compliance.yml
source_heading: Compliance
source_page: https://www.fiskil.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: FISKIL\naid: fiskil\nurl: https://www.fiskil.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.fiskil.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: on_request\n  text: Fiskil is compliant with leading industry security standards, including SOC 2 Type 2.\n- framework: other\n  type: ASAE 3150 Type II\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: on_request\n  text: ASAE 3150 Type II Processes in place to manage risk and secure systems.\n"
source_yaml_url: https://artifacts.apis.io/fiskil/compliance/fiskil-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from FISKIL's own page on 2026-11-09.
synthetic: false
tags:
- Open Banking
- Data Sharing
- Financial Services
- API Platform
- North America
---
