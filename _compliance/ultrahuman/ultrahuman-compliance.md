---
api_specs:
- filename: ultrahuman-metrics-api-openapi.yml
  format: yaml
  label: Ultrahuman Metrics API
  slug: ultrahuman-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ultrahuman/openapi/ultrahuman-metrics-api-openapi.yml
- filename: ultrahuman-user-api-openapi.yml
  format: yaml
  label: Ultrahuman User API
  slug: ultrahuman-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ultrahuman/openapi/ultrahuman-user-api-openapi.yml
- filename: ultrahuman-oauth-api-openapi.yml
  format: yaml
  label: Ultrahuman O Auth API
  slug: ultrahuman-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ultrahuman/openapi/ultrahuman-oauth-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO27001, GDPR, and HIPAA compliant.
    type: compliance claim
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO27001, GDPR, and HIPAA compliant.
    type: compliance claim
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO27001, GDPR, and HIPAA compliant.
    type: compliance claim
  trust_center:
    url: https://www.ultrahuman.com/security/
frameworks:
- GDPR
- HIPAA
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ultrahuman
provenance_date: '2026-11-10'
provider_name: Ultrahuman
provider_slug: ultrahuman
slug: ultrahuman-compliance
source_date: '2026-11-10'
source_filename: ultrahuman-compliance.yml
source_heading: Compliance
source_page: https://www.ultrahuman.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ultrahuman\naid: ultrahuman\nurl: https://www.ultrahuman.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ultrahuman-trust-center.yml\ntrust_center:\n  url: https://www.ultrahuman.com/security/\nattestations:\n- framework: ISO27001\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO27001, GDPR, and HIPAA compliant.\n- framework: GDPR\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO27001, GDPR, and HIPAA compliant.\n- framework: HIPAA\n  type: compliance claim\n \
  \ scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO27001, GDPR, and HIPAA compliant.\n"
source_yaml_url: https://artifacts.apis.io/ultrahuman/compliance/ultrahuman-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ultrahuman's own page on 2026-11-10.
synthetic: false
tags:
- Wearables
- Smart Ring
- Health
- Metabolic Health
- Sleep
- HRV
- Recovery
- CGM
- Glucose
- Digital Health
---
