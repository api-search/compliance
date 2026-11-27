---
api_specs:
- filename: offenders-io-search-api-openapi.yml
  format: yaml
  label: Offenders.io Search API
  slug: offenders-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offenders-io/openapi/offenders-io-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: SOC 2 Type 2 Compliant
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: null
  trust_center:
    url: https://trust.offenders.io/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Offenders.io
provenance_date: '2026-11-10'
provider_name: Offenders.io
provider_slug: offenders-io
slug: offenders-io-compliance
source_date: '2026-11-10'
source_filename: offenders-io-compliance.yml
source_heading: Compliance
source_page: https://trust.offenders.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Offenders.io\naid: offenders-io\nurl: https://trust.offenders.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/offenders-io-trust-center.yml\ntrust_center:\n  url: https://trust.offenders.io/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: SOC 2 Type 2 Compliant\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/offenders-io/compliance/offenders-io-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Offenders.io's own page on 2026-11-10.
synthetic: false
tags:
- Sex Offenders
- Public Safety
- Criminal Records
---
