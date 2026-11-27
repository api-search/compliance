---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent certified auditor
    period: null
    report_access: on_request
    scope: ProdPad service, Security, Confidentiality and Privacy
    text: ProdPad is fully SOC2 (Service Organization Control 2) Type II compliant, confirmed by an independent assessment by a certified auditor.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: ProdPad
    text: We are GDPR compliant
    type: compliance
  trust_center:
    url: https://www.prodpad.com/security/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ProdPad
provenance_date: '2026-11-10'
provider_name: ProdPad
provider_slug: prodpad
slug: prodpad-compliance
source_date: '2026-11-10'
source_filename: prodpad-compliance.yml
source_heading: Compliance
source_page: https://www.prodpad.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ProdPad\naid: prodpad\nurl: https://www.prodpad.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/prodpad-trust-center.yml\ntrust_center:\n  url: https://www.prodpad.com/security/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: ProdPad service, Security, Confidentiality and Privacy\n  period: null\n  issuer: independent certified auditor\n  report_access: on_request\n  text: ProdPad is fully SOC2 (Service Organization Control 2) Type II compliant, confirmed by an independent assessment\n    by a certified auditor.\n- framework: GDPR\n  type: compliance\n  scope: ProdPad\n \
  \ period: null\n  issuer: null\n  report_access: unstated\n  text: We are GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/prodpad/compliance/prodpad-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from ProdPad's own page on 2026-11-10.
synthetic: false
tags:
- Product Management
- Roadmaps
- Ideas
- Feedback
- OKRs
- Backlog
- Personas
---
