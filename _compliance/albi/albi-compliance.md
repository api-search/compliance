---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type I
    type: Type I
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II
  trust_center:
    url: https://trust.albiware.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Albi
provenance_date: '2026-11-09'
provider_name: Albi
provider_slug: albi
slug: albi-compliance
source_date: '2026-11-09'
source_filename: albi-compliance.yml
source_heading: Compliance
source_page: https://trust.albiware.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Albi\naid: albi\nurl: https://trust.albiware.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.albiware.com/\nattestations:\n- framework: SOC2\n  type: Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n"
source_yaml_url: https://artifacts.apis.io/albi/compliance/albi-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Albi's own page on 2026-11-09.
synthetic: false
tags:
- Restoration
- Software
- Software-as-a-Service
- Cloud
- Management
---
