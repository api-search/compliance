---
api_specs:
- filename: carte-v1alpha1-api-openapi.yml
  format: yaml
  label: Carte V1Alpha1 API
  slug: carte-v1alpha1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carte/openapi/carte-v1alpha1-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type II
    type: Type II
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SIG
    type: SIG
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: compliance
  trust_center:
    url: https://trust.carta.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Carte
provenance_date: '2026-11-09'
provider_name: Carte
provider_slug: carte
slug: carte-compliance
source_date: '2026-11-09'
source_filename: carte-compliance.yml
source_heading: Compliance
source_page: https://trust.carta.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Carte\naid: carte\nurl: https://trust.carta.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.carta.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: SOC1\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type II\n- framework: other\n  type: SIG\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: SIG\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n"
source_yaml_url: https://artifacts.apis.io/carte/compliance/carte-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Carte's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Equity
- Fund Management
---
