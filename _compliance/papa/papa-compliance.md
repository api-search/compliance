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
    text: SOC 2 Type 2
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://papa.securitypal.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Papa
provenance_date: '2026-11-10'
provider_name: Papa
provider_slug: papa
slug: papa-compliance
source_date: '2026-11-10'
source_filename: papa-compliance.yml
source_heading: Compliance
source_page: https://papa.securitypal.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Papa\naid: papa\nurl: https://papa.securitypal.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/papa-trust-center.yml\ntrust_center:\n  url: https://papa.securitypal.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/papa/compliance/papa-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Papa's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Social Care
- Companion Care
- Older Adults
- Medicare Advantage
- Medicaid
- Health Plans
- Aging
---
