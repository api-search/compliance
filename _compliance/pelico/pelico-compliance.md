---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 type 2 report
    type: SOC2 type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO 27001 : 2022'
    type: 'ISO 27001 : 2022'
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR
  trust_center:
    url: https://trust.pelico.ai/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pelico
provenance_date: '2026-11-10'
provider_name: Pelico
provider_slug: pelico
slug: pelico-compliance
source_date: '2026-11-10'
source_filename: pelico-compliance.yml
source_heading: Compliance
source_page: https://trust.pelico.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pelico\naid: pelico\nurl: https://trust.pelico.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.pelico.ai/\nattestations:\n- framework: SOC2\n  type: SOC2 type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 type 2 report\n- framework: ISO27001\n  type: 'ISO 27001 : 2022'\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO 27001 : 2022'\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/pelico/compliance/pelico-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Pelico's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Supply Chain
- Orchestration
- Artificial Intelligence
- ERP Integration
- Manufacturing Execution
---
