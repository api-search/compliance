---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 · Report on request
    type: Type I, Type II in progress
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise
    text: Business Associate Agreement
    type: Business Associate Agreement
  trust_center:
    url: https://replicas.dev/security
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Replicas
provenance_date: '2026-11-10'
provider_name: Replicas
provider_slug: replicas-dev
slug: replicas-dev-compliance
source_date: '2026-11-10'
source_filename: replicas-dev-compliance.yml
source_heading: Compliance
source_page: https://replicas.dev/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Replicas\naid: replicas-dev\nurl: https://replicas.dev/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://replicas.dev/security\nattestations:\n- framework: SOC2\n  type: Type I, Type II in progress\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 · Report on request\n- framework: HIPAA\n  type: Business Associate Agreement\n  scope: Enterprise\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Business Associate Agreement\n"
source_yaml_url: https://artifacts.apis.io/replicas-dev/compliance/replicas-dev-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Replicas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cloud
- Platform
- Development
---
