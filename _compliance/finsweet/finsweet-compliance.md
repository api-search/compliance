---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: 2024/25
    report_access: on_request
    scope: all paid products (CMS Bridge, Consent Pro, Finsweet Accounts, Finsweet Components, Wized)
    text: SOC 2 Type II — 2024/25
    type: SOC 2 Type II report
  - framework: SOC2
    issuer: null
    period: 2023/24
    report_access: on_request
    scope: null
    text: SOC 2 Type II — 2023/24
    type: SOC 2 Type II report
  - framework: SOC2
    issuer: null
    period: 2025/26
    report_access: on_request
    scope: null
    text: SOC 2 Type II — 2025/26
    type: SOC 2 Type II report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA compliance implemented
    type: HIPAA compliance program
  trust_center:
    url: https://trust.finsweet.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Finsweet
provenance_date: '2026-11-09'
provider_name: Finsweet
provider_slug: finsweet
slug: finsweet-compliance
source_date: '2026-11-09'
source_filename: finsweet-compliance.yml
source_heading: Compliance
source_page: https://trust.finsweet.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Finsweet\naid: finsweet\nurl: https://trust.finsweet.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.finsweet.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: all paid products (CMS Bridge, Consent Pro, Finsweet Accounts, Finsweet Components, Wized)\n  period: 2024/25\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II — 2024/25\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: 2023/24\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II — 2023/24\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope:\
  \ null\n  period: 2025/26\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II — 2025/26\n- framework: HIPAA\n  type: HIPAA compliance program\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliance implemented\n"
source_yaml_url: https://artifacts.apis.io/finsweet/compliance/finsweet-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Finsweet's own page on 2026-11-09.
synthetic: false
tags:
- Webflow
- Development
- Design
- Agency
- Software-as-a-Service
---
