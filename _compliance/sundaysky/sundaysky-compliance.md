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
    text: March 2026 SOC2 TYPE2 Report
    type: Type 2 report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.sundaysky.com/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SundaySky
provenance_date: '2026-11-10'
provider_name: SundaySky
provider_slug: sundaysky
slug: sundaysky-compliance
source_date: '2026-11-10'
source_filename: sundaysky-compliance.yml
source_heading: Compliance
source_page: https://trust.sundaysky.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SundaySky\naid: sundaysky\nurl: https://trust.sundaysky.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/sundaysky-trust-center.yml\ntrust_center:\n  url: https://trust.sundaysky.com/\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: March 2026 SOC2 TYPE2 Report\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/sundaysky/compliance/sundaysky-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from SundaySky's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Personalization
- Video Personalization
- Marketing
- Customer Experience
- Artificial Intelligence
- Enterprise
- Video Generation
- Media
- Analytics
- MarTech
---
