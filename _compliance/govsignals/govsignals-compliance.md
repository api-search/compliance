---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: FedRAMP High authorized platform
    text: FedRAMP High Authorized
    type: authorization
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Impact Level 5 controlled mission data (CUI)
    text: DoW IL5 Impact Level 5 · CUI
    type: DoW IL5 authorization
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II Report available for review
    type: Type II report
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Controlled technical data
    text: ITAR Controlled technical data
    type: ITAR
  trust_center:
    url: https://www.govsignals.ai/security/
frameworks:
- FedRAMP
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GovSignals
provenance_date: '2026-11-09'
provider_name: GovSignals
provider_slug: govsignals
slug: govsignals-compliance
source_date: '2026-11-09'
source_filename: govsignals-compliance.yml
source_heading: Compliance
source_page: https://www.govsignals.ai/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GovSignals\naid: govsignals\nurl: https://www.govsignals.ai/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.govsignals.ai/security/\nattestations:\n- framework: FedRAMP\n  type: authorization\n  scope: FedRAMP High authorized platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP High Authorized\n- framework: other\n  type: DoW IL5 authorization\n  scope: Impact Level 5 controlled mission data (CUI)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DoW IL5 Impact Level 5 · CUI\n- framework: SOC2\n  type: Type II report\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Report available for review\n- framework: other\n  type: ITAR\n  scope: Controlled technical data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ITAR Controlled technical data\n"
source_yaml_url: https://artifacts.apis.io/govsignals/compliance/govsignals-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from GovSignals's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Procurement
- Government
- Platform
---
