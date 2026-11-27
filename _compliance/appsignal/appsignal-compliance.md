---
api_specs:
- filename: appsignal-openapi-generated.yml
  format: yaml
  label: AppSignal API
  slug: appsignal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsignal/openapi/_ae-authored/appsignal-openapi-generated.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We’re ISO 27001 certified.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA compliant
    type: compliance
  trust_center:
    url: https://www.appsignal.com/security
frameworks:
- GDPR
- HIPAA
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AppSignal
provenance_date: '2026-11-09'
provider_name: AppSignal
provider_slug: appsignal
slug: appsignal-compliance
source_date: '2026-11-09'
source_filename: appsignal-compliance.yml
source_heading: Compliance
source_page: https://www.appsignal.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AppSignal\naid: appsignal\nurl: https://www.appsignal.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.appsignal.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re ISO 27001 certified.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant\n"
source_yaml_url: https://artifacts.apis.io/appsignal/compliance/appsignal-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from AppSignal's own page on 2026-11-09.
synthetic: false
tags:
- Monitoring
- Error Tracking
- Performance
- Observability
- Software-as-a-Service
---
