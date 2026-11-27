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
    text: SOC 2 Compliant
    type: Compliant
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: Compliant
  trust_center:
    url: https://trust.getmembrane.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Membrane
provenance_date: '2026-11-10'
provider_name: Membrane
provider_slug: membrane
slug: membrane-compliance
source_date: '2026-11-10'
source_filename: membrane-compliance.yml
source_heading: Compliance
source_page: https://trust.getmembrane.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Membrane\naid: membrane\nurl: https://trust.getmembrane.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/membrane-trust-center.yml\ntrust_center:\n  url: https://trust.getmembrane.com/\nattestations:\n- framework: SOC2\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: GDPR\n  type: Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/membrane/compliance/membrane-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Membrane's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- API Gateway
- Automation
- Integration
- No-Code
---
