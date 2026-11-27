---
claim_count: 2
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
    text: SOC 2 Type II Audit Report
    type: audit report
  trust_center:
    url: https://trust.fides.technology/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fides
provenance_date: '2026-11-09'
provider_name: Fides
provider_slug: fides
slug: fides-compliance
source_date: '2026-11-09'
source_filename: fides-compliance.yml
source_heading: Compliance
source_page: https://trust.fides.technology/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fides\naid: fides\nurl: https://trust.fides.technology/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.fides.technology/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: SOC2\n  type: audit report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Audit Report\n"
source_yaml_url: https://artifacts.apis.io/fides/compliance/fides-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Fides's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Governance
- Compliance
- Entity Management
---
