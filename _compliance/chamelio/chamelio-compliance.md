---
api_specs:
- filename: chamelio-openapi-generated.yml
  format: yaml
  label: Chamelio API
  slug: chamelio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chamelio/openapi/_ae-authored/chamelio-openapi-generated.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC2 Reports & Documents
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    source: https://www.chamelio.ai/security
    text: SOC 2 Type II
    type: Type II
  trust_center:
    url: https://trust.chamelio.ai/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Chamelio
provenance_date: '2026-11-09'
provider_name: Chamelio
provider_slug: chamelio
slug: chamelio-compliance
source_date: '2026-11-09'
source_filename: chamelio-compliance.yml
source_heading: Compliance
source_page: https://trust.chamelio.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Chamelio\naid: chamelio\nurl: https://trust.chamelio.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://trust.chamelio.ai/\n  - https://www.chamelio.ai/security\ntrust_center:\n  url: https://trust.chamelio.ai/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC2 Reports & Documents\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: Type II\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n\
  \  text: SOC 2 Type II\n  source: https://www.chamelio.ai/security\n"
source_yaml_url: https://artifacts.apis.io/chamelio/compliance/chamelio-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Chamelio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Software-as-a-Service
- Contracts
- Compliance
---
