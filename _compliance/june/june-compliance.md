---
api_specs:
- filename: june-companies-api-openapi.yml
  format: yaml
  label: June Companies API
  slug: june-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/june/openapi/june-companies-api-openapi.yml
- filename: june-events-api-openapi.yml
  format: yaml
  label: June Events API
  slug: june-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/june/openapi/june-events-api-openapi.yml
- filename: june-users-api-openapi.yml
  format: yaml
  label: June Users API
  slug: june-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/june/openapi/june-users-api-openapi.yml
- filename: june-pageviews-api-openapi.yml
  format: yaml
  label: June Pageviews API
  slug: june-pageviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/june/openapi/june-pageviews-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: We have one available upon request.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: June is GDPR ready.
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Comply with the CCPA, GDPR and sign a Data Processing Agreement (DPA).
    type: null
  trust_center:
    url: https://www.june.so/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: June
provenance_date: '2026-11-09'
provider_name: June
provider_slug: june
slug: june-compliance
source_date: '2026-11-09'
source_filename: june-compliance.yml
source_heading: Compliance
source_page: https://www.june.so/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: June\naid: june\nurl: https://www.june.so/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/june-trust-center.yml\ntrust_center:\n  url: https://www.june.so/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: We have one available upon request.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: June is GDPR ready.\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Comply with\
  \ the CCPA, GDPR and sign a Data Processing Agreement (DPA).\n"
source_yaml_url: https://artifacts.apis.io/june/compliance/june-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from June's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Product Analytics
- B2B SaaS
- Event Tracking
- Segment Compatible
- Retention
- Feature Adoption
- Activation
---
