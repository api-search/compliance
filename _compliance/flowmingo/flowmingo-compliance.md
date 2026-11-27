---
api_specs:
- filename: flowmingo-flowmingo-api-api-openapi.yml
  format: yaml
  label: Flowmingo Flowmingo API
  slug: flowmingo-flowmingo-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmingo/openapi/flowmingo-flowmingo-api-api-openapi.yml
- filename: flowmingo-scheduler-api-openapi.yml
  format: yaml
  label: Flowmingo Scheduler API
  slug: flowmingo-scheduler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmingo/openapi/flowmingo-scheduler-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR-compliant
    type: compliance claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2
    type: certification badge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CASA
    type: certification badge (CASA)
  trust_center:
    url: https://flowmingo.ai/security
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Flowmingo
provenance_date: '2026-11-09'
provider_name: Flowmingo
provider_slug: flowmingo
slug: flowmingo-compliance
source_date: '2026-11-09'
source_filename: flowmingo-compliance.yml
source_heading: Compliance
source_page: https://flowmingo.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Flowmingo\naid: flowmingo\nurl: https://flowmingo.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://flowmingo.ai/security\nattestations:\n- framework: GDPR\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR-compliant\n- framework: SOC2\n  type: certification badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2\n- framework: other\n  type: certification badge (CASA)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CASA\n"
source_yaml_url: https://artifacts.apis.io/flowmingo/compliance/flowmingo-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Flowmingo's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
