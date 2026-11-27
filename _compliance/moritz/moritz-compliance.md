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
    text: SOC 2 Type 2
    type: Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: ISO 27001:2022
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Moritz GDPR Attestation of Compliance.pdf
    type: Attestation of Compliance
  trust_center:
    url: https://trust.moritzlegal.com/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Moritz
provenance_date: '2026-11-10'
provider_name: Moritz
provider_slug: moritz
slug: moritz-compliance
source_date: '2026-11-10'
source_filename: moritz-compliance.yml
source_heading: Compliance
source_page: https://trust.moritzlegal.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Moritz\naid: moritz\nurl: https://trust.moritzlegal.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/moritz-trust-center.yml\ntrust_center:\n  url: https://trust.moritzlegal.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: ISO27001\n  type: ISO 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: GDPR\n  type: Attestation of Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n \
  \ text: Moritz GDPR Attestation of Compliance.pdf\n"
source_yaml_url: https://artifacts.apis.io/moritz/compliance/moritz-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Moritz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Law Firms
- Artificial Intelligence
- Contracts
- Y Combinator
---
