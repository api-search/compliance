---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type2
    type: report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: regulation
  trust_center:
    url: https://caddi.com/en-us/security/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CADDi
provenance_date: '2026-11-09'
provider_name: CADDi
provider_slug: caddi
slug: caddi-compliance
source_date: '2026-11-09'
source_filename: caddi-compliance.yml
source_heading: Compliance
source_page: https://caddi.com/en-us/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CADDi\naid: caddi\nurl: https://caddi.com/en-us/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://caddi.com/en-us/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001\n- framework: SOC2\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type2\n- framework: GDPR\n  type: regulation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/caddi/compliance/caddi-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from CADDi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Industrial
- Manufacturing
- Procurement
- Supply Chain
- Engineering Data
- Artificial Intelligence
---
